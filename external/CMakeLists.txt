add_subdirectory(json)
add_subdirectory(args)
add_library(glm INTERFACE IMPORTED GLOBAL)
target_include_directories(glm INTERFACE glm)
