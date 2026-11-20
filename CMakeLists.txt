<<<<<<< HEAD
cmake_minimum_required(VERSION 3.14)
project(CommandEngine LANGUAGES CXX)
=======
cmake_minimum_required(VERSION 3.20)
project(WrapperEngineProject LANGUAGES CXX)
>>>>>>> 3ff5af33788ea874c9cf8183462fa11cd8e0b5a9

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

<<<<<<< HEAD
add_executable(app Source.cpp)
=======
add_executable(wrapper_app src/main.cpp)
add_test(NAME BaseExecutionTest COMMAND wrapper_app)
>>>>>>> 3ff5af33788ea874c9cf8183462fa11cd8e0b5a9
