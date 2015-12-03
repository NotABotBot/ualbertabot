/***************************************
*	NotABot ReadMe
*	Maciej Ogrocki, Randy Wong, 
*	Brandon Smolley, Sabrina Gannon
***************************************/

/**************************************
*	How to Compile and Run
***************************************/
Simply importing the project in Visual Studio and compiling the project is sufficient,
there were no special requirements needed to run and compile during testing.

/**************************************
*	Modules Changed / Created:
***************************************/

StrategyManager 	 getNotABotBuildOrderGoal()
ProductionManager 	 update(), detectBuildOrderDeadlock() 
Squad			 calcRegroupPosition()
RangedManager 		 kiteTarget()
MeleeManager		 executeMicro(), meleeUnitStepOff() 

BuildingPlacer		 getBuildLocationNear(), drawPylon(), drawForge(), 
			 drawPhotonCannon(), drawGateway(), findHome(), findChoke()
			 
MicroManager		 smartHighTemplarAttackUnit(), smartAttackUnit(), smartAttackMove(), smartMove()

