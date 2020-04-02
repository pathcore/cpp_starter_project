find_package(fmt REQUIRED)

# Generic main that uses fmtlib
add_executable(intro main.cpp)
target_link_libraries(
  intro PRIVATE project_options project_warnings fmt::fmt)
