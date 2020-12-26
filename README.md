# Tower-of-Saviors-in-C
## Input
The input start with 6 members in your team. Each team member will give it'sTITLE, NAME, TYPE, ATTACK and RECOVERY. As sample input, the begin and the end ofTITLEis "----"; Other informations are tailing after " : ". After the team members, it will be "--------------------". Notice that you may only give the LEADER and SUPPORTER. The MEMBER can be None.

The next N line is a 6 charactors string until "------", which are Runestones preparing for falling to stage. Your stage is under "------", a 5*6 2D charactor array.

Runestones are 6 types. In the input, the uppercases stand for Reinforced Runestones, and the lowercases are normal Runestones.

Water : W w
Fire : F f
Earth : E e
Light : L l
Dark : D d
Health : H h

## Output
You should count each member's final Damage and Recovery. Then, output the member from the large Damage to the small Damage. (you can use qsort to complete this operation)

The members should output between 43 "-". Member name should be printed between two "|" first, and you should make sure that there must be 41 characters between two "|". The next line should output Damage and Recovery. Also, between every two "|" should contain 20 characters.
