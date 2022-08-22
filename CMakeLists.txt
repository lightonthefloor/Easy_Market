cmake_minimum_required(VERSION 3.23)
project(Easy_Market C)

set(CMAKE_C_STANDARD 17)

add_executable(Easy_Market main.c Libs/Src/Customers.c Libs/Inc/Customers.h Libs/Src/Manager.c Libs/Inc/Manager.h Libs/Src/Product.c Libs/Inc/Product.h Libs/Src/Order.c Libs/Inc/Order.h)

include_directories(Libs/Inc)
