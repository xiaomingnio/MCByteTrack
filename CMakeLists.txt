cmake_minimum_required(VERSION 3.5)
project(bytetrack-opencv-cpp)
#set(CMAKE_CXX_STANDARD 11)

#opencv
set(OpenCV_DIR /home/*/workspace-cpp/opencv4.6/install/lib/cmake/opencv4)
find_package(OpenCV REQUIRED)

include_directories(${OPENCV_INLCUDE_DIR})
link_directories(${OPENCV_LIB_DIR})

include_directories(include)
include_directories(/usr/local/include/eigen3)

file(GLOB My_Source_Files src/*.cpp)
add_executable(bytetrack-opencv-cpp ${My_Source_Files})
target_link_libraries(bytetrack-opencv-cpp ${OpenCV_LIBS})
