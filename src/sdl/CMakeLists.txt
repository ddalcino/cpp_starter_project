add_executable(test_sdl main.cpp)

install_local_conanfile()

target_link_libraries(test_sdl PRIVATE CONAN_PKG::sdl2)
