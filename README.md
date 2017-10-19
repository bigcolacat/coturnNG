This project is based on coturn (https://github.com/coturn/coturn), for more information about TURN/STUN, please read the documents provided by coturn project.

Because it is based on coturn, and add more functionalities, so it is called "coturnNG".

In this project, it focuses the following changes:
	1. Based on C++, reuse the existed STL containers, to make the codes more simple.

	2. Modulized features, provide interfaces to implement module.

	3. Support runtime configuration changes by using centrolized config server.

	4. Add more integration test tools, have more confidence after making changes by running the tools.
