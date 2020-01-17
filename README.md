# Fire-Will-Kill-Us-All

"Fire Will Kill Us All" is a collaborative project, which me and 4 others made for university.

NOTE: The classes I personally worked on are:

	-Dijkstra.cs (Dijkstra algorithm implementation)
	-Extinguisher.cs (The code for the fire extinguisher)
	-Pathfinding.cs (A* algorithm implementation)
	-Person.cs (The code for all people)
	-Unit tests for the above classes

The application allows users to create their own floor/room layout, along with different walls, doors, fire escapes and
fire extinguishers. Next, it allows them to spawn people, either manually or randomly.

The simulation is created to see what could happen in the event of a fire. The fire can be added manually or spawned randomly.
The app is designed to help people plan how and where to place fire escapes and extinguishers, so that if a fire occurs,
the survival rate is as high as possible.

Along with the simulation, there is a statistics window, which logs all important events. In the end of a simulation,
the user can choose to save the statistical report into a txt file.

Additionally, the app has the possibility to be connected to a Unity player for better 3D visual effects. This functionality,
however, is optional and not required.

There are 4 personality types for people:

	-Pussy - spawns 68% of the time. Will run for the exit only, if exit is blocked, will panic and run in circles.
	-Selfish - spawns 20% of the time. Will run for the exit, if exit is blocked, then will run towards an extinguisher.
	-Hero - spawns 10% of the time. Runs for the extinguisher immediately, if no extinguishers/path is blocked, will run for exit.
	-Shaggy from Scooby-Doo - Easter egg, spawns only 2% of the time. Does nothing but run in circles.
