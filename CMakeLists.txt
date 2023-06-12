cmake_minimum_required(VERSION 3.25)
project(RayTracinginoneweekend)

set(CMAKE_CXX_STANDARD 17)
include_directories(../src)


add_executable(test_ppm_image test/test_ppm_image.cpp)
add_executable(test_vec3_color test/test_vec3_color.cpp)
add_executable(test_ray test/test_ray.cpp)
add_executable(test_normal test/test_normal.cpp)
add_executable(test_hittables test/test_hittables.cpp)
add_executable(test_diffuse test/test_diffuse.cpp)
add_executable(test_material test/test_material.cpp)
add_executable(test_wide_camera test/test_wide_camera.cpp)
add_executable(final_render main.cpp)

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)