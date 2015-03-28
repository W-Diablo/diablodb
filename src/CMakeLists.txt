aux_source_directory(db SRC_DIRS)
message(STATUS "out put dir" ${PROJECT_BINARY_DIR})
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)
add_library(diablodb ${SRC_DIRS})
