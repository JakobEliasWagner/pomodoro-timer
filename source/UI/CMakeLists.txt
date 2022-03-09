target_sources(ui
        PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/ui_test.cpp
        ${CMAKE_CURRENT_LIST_DIR}/ui_test.h
        )

target_include_directories(ui
        PUBLIC
        ${CMAKE_CURRENT_LIST_DIR})