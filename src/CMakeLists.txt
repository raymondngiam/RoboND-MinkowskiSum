add_executable(minkowski_sum minkowski_sum.cpp)
target_link_libraries(minkowski_sum
  Python3::Python
  Python3::NumPy
  )
