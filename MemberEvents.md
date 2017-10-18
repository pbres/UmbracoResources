
## Creating member
        [CreateWithMembershipProvider](http://bit.ly/2yDX4mD) -> creates empty member withour properties and below methods are called: 
          - [CreateWithIdentity](http://bit.ly/2gb6nm9) which triggers events: 1)saved 2)created http://bit.ly/2xwioKo 
          - [Save method](http://bit.ly/2ydOD07): still without properties(save event is triggered second time) 
         all that return to [MemberController](http://bit.ly/2hAi2YE) and save event is triggered once again with properties 

        So below function is used to determine whether we reach save event with custom properties(so property.Value will not be null any more) 

        public override bool IsInitialized()
        {
            var property = _umbracoMember.Properties[Constants.Alias.MemberIsInitialized];
            if (property.Value == null)
            {
                return false;
            }
            return true;
        }