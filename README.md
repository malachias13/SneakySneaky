# SneakySneaky

### Sneaky sneaky is a small prototype that depict the versatility of a Hierarchical State Machine shown in NPCs (non-player characters). 
![Level](https://user-images.githubusercontent.com/69220988/170120401-87fe95e1-d58c-4e1b-b201-3dd6c29574d9.png)
A simple prototype level to display Ai capabilities.

## Hierarchical State Machine 
![StateComps](https://user-images.githubusercontent.com/69220988/170120352-1da15c40-3708-4a1e-a685-c22ce6825c10.png)
![image](https://user-images.githubusercontent.com/69220988/170121362-5f972204-b4a5-4565-97da-48973f6ea39b.png)
AI states are encapsulated inside of components, which are parented to the Guards.

![StateEvents](https://user-images.githubusercontent.com/69220988/170122831-cb4c393b-0504-458b-abdc-342550f14796.png)

Each state contains events that handles all functionality of the state. All events are called inside of the state machine component class.


## AI Distracted
![AI Distract](https://user-images.githubusercontent.com/69220988/170116606-15e79f88-c41c-488e-9004-9137cdef8f09.gif)

When the player presses 3 on a selected NPC, the NPC will transition to “AC_State_angry” and move towards the nearest flashing cube.

## AI Attack
![AI Kills player](https://user-images.githubusercontent.com/69220988/170118392-c1846e73-c196-4490-8c0c-1f2c90aea904.gif)

## AI sight perception
![AI Chase](https://user-images.githubusercontent.com/69220988/170118845-3d4680bc-1fb5-45ec-9842-f2cc0636b4ec.gif)

## AI patrol
![AI revese patrol](https://user-images.githubusercontent.com/69220988/170119215-f18ef683-82ec-4f27-82e0-cc8e45233448.gif)
