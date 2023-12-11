find_package(GTest REQUIRED)

add_executable(dones main.cpp)
target_link_libraries(dones adds GTest::GTest GTest::Main) 
