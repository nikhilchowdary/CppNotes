set(HEADERS
   ${HEADERS}
   ${CMAKE_CURRENT_SOURCE_DIR}/basics.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/boolean.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/chartype.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/const.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/inttype.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/linkedlist.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/stack.hpp
   ${CMAKE_CURRENT_SOURCE_DIR}/concurrentmap.hpp
   PARENT_SCOPE
)

set(SOURCES
   ${SOURCES}
   ${CMAKE_CURRENT_SOURCE_DIR}/const.cpp
   PARENT_SCOPE
)
