add_library(bloom INTERFACE)
target_include_directories(bloom INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

add_library(ArashPartow::bloom ALIAS bloom)
