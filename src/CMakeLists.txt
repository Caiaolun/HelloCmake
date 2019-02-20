include_directories(${PROJECT_SOURCE_DIR}/lib)
set(APP_SRC main.c)
add_executable(hello ${APP_SRC})
#减少中间文件,,也就是说不会生成.a 在这里放着
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)
target_link_libraries(hello libhello)
