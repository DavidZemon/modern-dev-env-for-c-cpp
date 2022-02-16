CLion Demo
----------

### Demo 1

* map conan profile
* run cmake
* select unit test and execute


* add dyn alloc to JumpstartedSkeleton.cpp
* see failing unit test
* add debug configuration
* place conditional breakpoint on return statement
* switch to debug mode
* show memory view on newLhs and &rhs
* run to completion
* show valgrind parsing

### Demo 2

* Set run configuration (RELEASE and debug)
* Note the tmp directory
* SSH in and execute conan
* Reload CMake
* Open JumpstartedSkeletonTest.cpp
* Jump to TEST_F
* "open in terminal"
* Switch to debug context
* Compile all
* Note clang-tidy warnings
* Run code coverage
* Set breakpoint
* Remote debug

Additional Integrations
-----------------------

* Docker-based toolchain
* Remote GDB

* clang-tidy
* cppcheck
* valgrind target
