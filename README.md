# The Legend Of Viking

# Environment
Platform Windows\
Architecture Intel-64bit

# How  To Play
## Movement
**WASD** to move player\
ADD **LEFTSHIFT** to run\
**SPACE** to jump
## Attack
**X** to chop enemy\
**C** to double chop enemy\
**V** to spin attack enemy\
**F** to collect coin
## Option
**P** to play/stop music

# Bonus
## Music
 music include footstep and BGM
## Good game structure code
component-oriented
```
public class CharacterStats : MonoBehaviour
...
public class PlayerStats :CharacterStats
...
public class EnemyStats : CharacterStats
...
```
## How good my game is
* run in the instant of enenmy attacking avoids minus blood\
* different attack mode\
* enemy stops while too far away from player\
* add enemy animator while being attack
* nice UI
