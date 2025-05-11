cmake_minimum_required(VERSION 3.31)
project(ATMSystem)

set(CMAKE_CXX_STANDARD 26)

add_executable(ATMSystem main.cpp
        "Account Class/Account.cpp"
        "Account Class/Account.h"
        "System Class/System.cpp"
        "System Class/System.h"
        Encryption/Base64.h
        Encryption/Base64.cpp
        Encryption/encrypt.h
        Encryption/vigenere.h
        Login/Login.cpp
        Login/Login.h)
