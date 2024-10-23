cmake_minimum_required(VERSION 3.0)
project(embe)

set(CMAKE_CXX_STANDARD 11)

# Add your executable or library
add_executable(embe embe.cpp)

# If you're linking to other libraries, for example, pthread:
# target_link_libraries(mypackage pthread)
install(TARGETS embe DESTINATION bin)
