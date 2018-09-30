# SensorNetworkToMinCostFlow
Research Project for CSC500 Research Method - CSUDH

This is a tentative commit. A code cleaning will be done later.

How to run:

1. Compile
$ javac *.java

2. Run
$ java SensorNetwork

Note:
1. All the inputs now is hard coded. It will change to take user input later.
2. All edges are assumed to have same minimum capacity
3. Using Random Seed, so we can get the same Sensor Network graph. The current graph is suitable for our demostration. You are welcome to try other seed.

Reference:
The project is a modification on a Sensor Network Generator Program is provided by Professor Bin Tang. The modification is to add a conversion algorithm to convert the generated sensor network to an input of minimum cost flow algorithm - cs2-4.6
Original Dijkastra Implementation:
http://www.marcinkossakowski.com/finding-shortest-path-using-dijkstras-algorithm/
