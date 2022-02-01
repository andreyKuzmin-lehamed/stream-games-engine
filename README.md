# stream-games-engine
Game engine for development games with remote control for stream viewers

# Documentation

## Classes

## GAME
Static class for updating gameobjects state in every cycle.
## COLLISION_HANDLER
Static class for detecting all collisions between all gameobjects in every game cycle iteration. 
## ADAPTER
Static class for receiving remote command from stream viewers.
## RENDER
Static class for rendering every DOM changes in every game cycle iteration.
## ANIMATOR
Static class for changing rig positions of all gameobjects in every game cycle iteration.
## DATABASE
Static class for saving and loading data. 
## VARIABLES
Static class for references to often used names.
## SETTINGS
Static class for customizing base game settings.
## CONNECTION
Static class for connecting to back-end server.
## STATISTIC
Static class for get game statistic (fps, uptime, etc.)
## TIME
Static class for handling delta time.

## Gameobject
Class for customizing base settings of gameobjects.
## ActorObject
Class extended from Gameobject, keep settings and methods of actors (players, monsters, etc.)
## InteractiveObject
Class extended from Gameobject, keep settings and methods of interactive objects (chests, buttons, items, etc.)
## StateMachine
Class for handling state of gameobject.
## State
Class for customizing base settings of state.
### IdleActorState
Class extended from State, keep settings and methods of idle state of actor.
### MoveActorState
Class extended from State, keep settings and methods of move state of actor.
### FightActorState
Class extended from State, keep settings and methods of fight state of actor.
### InteractionActorState
Class extended from State, keep settings and methods of interaction state of actor.
### DeathActorState
Class extended from State, keep settings and methods of death state of actor.
## Rig
Class for handling position and rotations of gameobject achor points. 
## Skin
Class for handling image sources of gameobject.
## Animation
Class for describing animation variant.




