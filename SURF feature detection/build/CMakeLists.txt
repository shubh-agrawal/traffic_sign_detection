cmake_minimum_required(VERSION 2.8)
project( surf_detector )
find_package( OpenCV REQUIRED )
add_executable( ../surf_detector ../surf_detector.cpp )
target_link_libraries( ../surf_detector ${OpenCV_LIBS} )


