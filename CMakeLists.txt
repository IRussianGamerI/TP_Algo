CMAKE_MINIMUM_REQUIRED(VERSION 3.10)
project(Graph)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(test_graph 
        src/main.cpp 
        src/graphFunctions.cpp 
        src/ListGraph.cpp 
        src/MatrixGraph.cpp
        src/SetGraph.cpp 
        src/ArcGraph.cpp)
