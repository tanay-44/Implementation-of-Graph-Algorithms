# Implementation-of-Graph-Algorithms
Implementation of FPT Algorithm for kXr Grid Embedding Problem

--> Check_planarity.cpp file can check for the planarity of the graph, if its not planar it outputs the kuratowski subgraph (K5 or K3,3) using the boyer myrvold planarity testing.

--> In the project folder to run the program,use command(Generalized commands just use brew/sudo/vcpkg according to your system):
  1) First install boost library using: brew install boost
  2) Then install graphviz using      : brew install graphviz
  3) Then run the files using :
     g++ driver.cpp check_planar.cpp check_isomorphism.cpp -o graph_program -I$(brew --prefix boost)/include -L$(brew --prefix boost)/lib -lboost_graph && ./graph_program
  4) For getting the dot file in the form of png file with a graph drawing use: dot -Tpng graph.dot -o graph.png
