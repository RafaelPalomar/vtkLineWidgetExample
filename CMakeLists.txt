cmake_minimum_required(VERSION 2.8)

project(vtkLineWidgetExample)

find_package(VTK REQUIRED)

include(${VTK_USE_FILE})

add_executable(vtkLineWidgetExample
  main.cxx
  )

target_link_libraries(vtkLineWidgetExample
  ${VTK_LIBRARIES}
  )