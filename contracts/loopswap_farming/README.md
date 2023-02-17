# LoopSwap Farming

## Overview
  LoopSwap comes with the feature of Staking LP tokens and earning the reward in the 
form of various reward tokens. 
User needs some "LP Tokens" to enter into a Farm with. Farms can only accept their 
own exact LP Token. For example, the LOOP-UST Farm will only accept LOOP-UST 
LP Tokens. To get the exact LP Token, user will need to provide liquidity for that trading 
pair.  
Main functionalities are given below: 
-  Users can stake the LP tokens. 
-  Admin decides the Number of total reward tokens to be distributed to the pool 
as a reward. 
- The distribute function is called after which reward tokens will be distributed. 
- Proportionate to user’s staked LP tokens as compared to the total USD value of 
the reward pool, user share in pool reward will be calculated. 
-  User can then unstake and claim his reward. 
