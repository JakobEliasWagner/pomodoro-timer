add_library(imgui "")
set_target_properties(imgui PROPERTIES LINKER_LANGUAGE CXX)
target_sources(imgui
        PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/imgui/imgui.h
        )
target_include_directories(imgui
        PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/imgui)