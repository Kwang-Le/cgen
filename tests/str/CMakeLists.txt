add_executable(spaces_ut spaces_ut.c)
add_executable(split_ut split_ut.c)
foreach (p spaces_ut split_ut)
  target_link_libraries(${p} bkc)
endforeach()