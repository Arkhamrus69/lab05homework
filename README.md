[![CI](https://github.com/Arkhamrus69/lab05homework/actions/workflows/ci.yml/badge.svg)](https://github.com/Arkhamrus69/lab05homework/actions/workflows/ci.yml)
[![Coverage Status](https://coveralls.io/repos/github/Arkhamrus69/lab05homework/badge.svg?branch=main)](https://coveralls.io/github/Arkhamrus69/lab05homework?branch=main)

#Проверочка 1:
```sh
Internal ctest changing into directory: /home/vboxuser/Рабочий стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build
UpdateCTestConfiguration  from :/home/vboxuser/Рабочий стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build/DartConfiguration.tcl
UpdateCTestConfiguration  from :/home/vboxuser/Рабочий стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build/DartConfiguration.tcl
Test project /home/vboxuser/Рабочий стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build
Constructing a list of tests
Done constructing a list of tests
Updating test list for fixtures
Added 0 tests to meet fixture requirements
Checking test dependency graph...
Checking test dependency graph end
test 1
    Start 1: check

1: Test command: /home/vboxuser/Рабочий\ стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build/check
1: Working Directory: /home/vboxuser/Рабочий стол/arkhamrus69@gmail.com/workspace/projects/lab05homework/_build
1: Test timeout computed to be: 10000000
1: Running main() from gmock_main.cc
1: [==========] Running 3 tests from 2 test cases.
1: [----------] Global test environment set-up.
1: [----------] 1 test from Account
1: [ RUN      ] Account.SimpleTest
1: [       OK ] Account.SimpleTest (0 ms)
1: [----------] 1 test from Account (0 ms total)
1: 
1: [----------] 2 tests from Transaction
1: [ RUN      ] Transaction.SimpleTest
1: 2 send to 1 $500
1: Balance 2 is 500
1: Balance 1 is 50
1: 2 send to 1 $300
1: Balance 2 is 100
1: Balance 1 is 350
1: [       OK ] Transaction.SimpleTest (0 ms)
1: [ RUN      ] Transaction.Mock
1: 2 send to 1 $500
1: Balance 2 is 500
1: Balance 1 is 50
1: 2 send to 1 $300
1: Balance 2 is 100
1: Balance 1 is 350
1: [       OK ] Transaction.Mock (1 ms)
1: [----------] 2 tests from Transaction (1 ms total)
1: 
1: [----------] Global test environment tear-down
1: [==========] 3 tests from 2 test cases ran. (1 ms total)
1: [  PASSED  ] 3 tests.
1/1 Test #1: check ............................   Passed    0.00 sec

100% tests passed, 0 tests failed out of 1

Total Test time (real) =   0.00 sec
```
#Проверочка 2:
```sh
[  7%] Building CXX object banking/CMakeFiles/account.dir/Account.cpp.o
[ 14%] Linking CXX static library libaccount.a
[ 14%] Built target account
[ 21%] Building CXX object banking/CMakeFiles/transaction.dir/Transaction.cpp.o
[ 28%] Linking CXX static library libtransaction.a
[ 28%] Built target transaction
[ 35%] Building CXX object third-party/gtest/googlemock/gtest/CMakeFiles/gtest.dir/src/gtest-all.cc.o
[ 42%] Linking CXX static library libgtest.a
[ 42%] Built target gtest
[ 50%] Building CXX object third-party/gtest/googlemock/CMakeFiles/gmock.dir/src/gmock-all.cc.o
[ 57%] Linking CXX static library libgmock.a
[ 57%] Built target gmock
[ 64%] Building CXX object third-party/gtest/googlemock/CMakeFiles/gmock_main.dir/src/gmock_main.cc.o
^[[A[ 71%] Linking CXX static library libgmock_main.a
[ 71%] Built target gmock_main
[ 78%] Building CXX object CMakeFiles/check.dir/tests/test1.cpp.o
^[[A^[[A[ 85%] Linking CXX executable check
[ 85%] Built target check
[ 92%] Building CXX object third-party/gtest/googlemock/gtest/CMakeFiles/gtest_main.dir/src/gtest_main.cc.o
^[[A[100%] Linking CXX static library libgtest_main.a
[100%] Built target gtest_main
```


