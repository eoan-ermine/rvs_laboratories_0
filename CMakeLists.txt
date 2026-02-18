project(rvs_laboratories_0)

find_package(CUDA REQUIRED)

cuda_add_executable(rvs_laboratories_0 rvs_laboratories_0/main.cu)
