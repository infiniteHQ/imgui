add_library(imgui STATIC 
	imgui.cpp
	imgui_demo.cpp
	imgui_draw.cpp
	imgui_tables.cpp
	imgui_widgets.cpp
	backends/imgui_impl_sdl.cpp
	backends/imgui_impl_vulkan.cpp
	misc/nodes/crude_json.cpp
	misc/nodes/imgui_canvas.cpp
	misc/nodes/imgui_node_editor_api.cpp
	misc/nodes/imgui_node_editor.cpp
	misc/text_editors/text_editor.cpp
)

target_include_directories(imgui PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")
