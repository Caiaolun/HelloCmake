#project(HELLO)
#set(SRC_LIST main.c hello.c)
#add_executable(hello ${SRC_LIST})


#project(HELLO)
#set(LIB_SRC hello.c)
#set(APP_SRC main.c)
#add_library(libhello ${LIB_SRC})
#add_executable(hello ${APP_SRC})
#target_link_libraries(hello libhello)


#project(HELLO)
#add_subdirectory(src)
#add_subdirectory(lib)


project(HELLO)
add_subdirectory(src bin)
add_subdirectory(lib)
