cmake_minimum_required(VERSION 3.5.0)
project(ridgeback_description)

find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY meshes/
  DESTINATION ${PROJECT_NAME}/share/meshes
)

install(DIRECTORY urdf/
  DESTINATION ${PROJECT_NAME}/share/urdf
)
