add_library(ui "")

include(${CMAKE_CURRENT_LIST_DIR}/UI/CMakeLists.txt)

add_executable(timer "")
target_sources(timer
        PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/main.cpp
        )
target_link_libraries(timer
        PRIVATE
        ui
        imgui)