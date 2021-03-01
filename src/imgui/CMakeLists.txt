# imgui test executable, with full warnings enabled
add_executable(test_imgui test.cpp)

install_local_conanfile()

target_link_libraries(test_imgui PRIVATE project_warnings project_options CONAN_PKG::imgui-sfml)
