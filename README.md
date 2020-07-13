# 2D side scrolling shooter created in Unity (C#) with Visual Studio.  

Senior Design Project for Computer Graphics (CS179N) course at UCR   
5-man group game development in Agile. (Team Lead)  

## Team:  
* JaeHyun Park  
* Tom Shih  
* Bryan Nguyen  
* Jason Chan  
* Daniel Li  

## Scripts:  

ArmRotation- Rotates player’s arm based on mouse position to aim weapon  
AudioManager- Plays game music  
CharacterController2D- Handles player collision, jumping, player direction  
EnemyDetection- Used for flying type enemy to detect the player  
EnemyMovement- Controls grounded enemy movement  
EnemyProjectile- Information for projectile type enemy  
EnemyShoot- Handles projectile type enemy shooting  
EnemyChaseDamage- Damages player  
EnemyDummyDamage- Damages player  
EnemyFlyingDamage- Damages player    
EnemyFlip- Flip enemy sprite based on the direction it is moving    
AIDestinationSetter- A* algorithm to path to player    
GameMaster- Handles player/enemy death and player respawn    
GameTimeScript- Tracks time spent in level  
HealthBar- UI element that shows the player’s health  
HealthIncrease- Called when player picks up health  
LevelSelector- Selects level to play  
MainMenu- Main menu  
NextScene- Transports player to the next level when current one is completed  
PauseMenu- Contains scripts for the pause menu  
Player- Contains stats of the player as well as handling damage / respawning  
PlayerMovement- Handles player jumping and moving left/right  
RespawnSetActive- Respawns player   
Score- Tracks the player’s score for the level  
UpgradeWeapon- Increases weapon damage  
Weapon- Basic weapon implementation with damage, fire rate, etc… Also handles shooting  
WeaponPickUp- Allows players to pick up weapons from the ground.  
WeaponSwitch- Allows user to switch between weapons that the player picked up  

## Algorithms:  
We used the A* search algorithm used to path our flying enemies. Unity has its own pathfinding algorithm, but since one of our members had experience with the A* package, we decided to use that instead.  

## Feature Implementations:  
-Weapons System  
-Sound System  
-Health System  
-game UI/UX  
