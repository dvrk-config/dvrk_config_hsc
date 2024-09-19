cmake_minimum_required (VERSION 3.10)
project (dvrk_config_hsc VERSION 2.3.0)

find_package (ament_cmake QUIET)
if (ament_cmake_FOUND)
  ament_package ()
endif ()

install (
  DIRECTORY hsc-dVRK hsc-daVinci
  DESTINATION share
  )
