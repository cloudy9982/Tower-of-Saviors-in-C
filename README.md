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

### test
test1:

----LEADER----
NAME : Cauldron of Divinity - Tuo Ba Yu-Er
TYPE : Fire
ATTACK : 1497
RECOVERY : 451
----MEMBER1----
NAME : Lamentable Clairvoyant - Cassandra
TYPE : Water
ATTACK : 1372
RECOVERY : 474
----MEMBER2----
NAME : Scourge of Transfiguration - Circe
TYPE : Earth
ATTACK : 1356
RECOVERY : 402
----MEMBER3----
NAME : Chen Jing-Ciou, Young Last Prince
TYPE : Earth
ATTACK : 1289
RECOVERY : 475
----MEMBER4----
NAME : Land Overlord Duncan
TYPE : Earth
ATTACK : 1100
RECOVERY : 386
----SUPPORTER----
NAME : Stone of Origin - Syu Siao-Syue
TYPE : Water
ATTACK : 1462
RECOVERY : 481
--------------------
fDlflw
FDwfdf
FHwedf
ddHedH
FHweDf
FHwdDf
lHldDH
ldwdlh
lwWhld
------
wwwlhh
wfwhhh
wheehd
lllldf
ffffef

test2:

----LEADER----
NAME : Athena, Goddess of Warfare
TYPE : Earth
ATTACK : 1516
RECOVERY : 376
----MEMBER1----
NAME : None
TYPE : None
ATTACK : 0
RECOVERY : 0
----MEMBER2----
NAME : None
TYPE : None
ATTACK : 0
RECOVERY : 0
----MEMBER3----
NAME : None
TYPE : None
ATTACK : 0
RECOVERY : 0
----MEMBER4----
NAME : None
TYPE : None
ATTACK : 0
RECOVERY : 0
----SUPPORTER----
NAME : Athena, Goddess of Warfare
TYPE : Earth
ATTACK : 1516
RECOVERY : 376
--------------------
feHHWl
WdDEwD
hHLLFE
DFFdEh
FHheeD
dDDfEL
wLddEE
HdLlle
dlEfeE
hhHFEH
LdHDEL
fFEWEf
hwLfDl
hEhDEd
eHDwEf
HHFdeW
heHeLf
ldwdEw
HHdhEL
lwdwEl
effWED
DLLfef
FHHFED
lWDHeE
HwfWEw
DeDfeF
lDfEEd
lWFEef
WDElEe
FDfLeW
HweHew
hElhEl
lHldEh
hWwEed
WeDwEE
flwHeD
lWFfel
LleeEL
eLEEeE
EwWWEl
EeeEEE
WeEEeE
EeEEhH
EHEdhE
eEEEHl
EEwEeE
wfeeEe
EeEeEe
EeWEee
EeEeEE
eEweeE
------
EwwfEe
ddeeEw
Ewwwdd
EDdhhh
eeEeff
