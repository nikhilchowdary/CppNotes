add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/ctci")
add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/euler")

set(HEADERS
   ${HEADERS}
   ${CMAKE_CURRENT_SOURCE_DIR}/factorial.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/bitsmanipulation.hpp
   PARENT_SCOPE
)

set(SOURCES
   ${SOURCES}
   ${CMAKE_CURRENT_SOURCE_DIR}/factorial.cpp
   PARENT_SCOPE
)
