add_executable(Analysis main.cpp main.cpp)
target_link_libraries(Analysis ib9jho_library)
target_include_directories(Analysis PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../src)
