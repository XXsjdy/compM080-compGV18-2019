# Coursework 1 F&Q list


1. loading PLY: you can also use igl::readPLY and igl::readPLY and writePLY.
example of loading a .off file in the previous tutorials
[practices_flann/src/main.cpp#L31](https://github.com/smartgeometry-ucl/compM080-compGV18-2019/blob/master/tutorial_002/cpp/practices_flann/src/main.cpp#L31)

2. sub-sampling step in ICP: we suggest you start with non-subsampling step (use all input points if your machine allows). After your implementation looks work, you can try sub-sampling and answer item `4. Instead of directly aligning...` 

3. rejection step in ICP: a simple one is to check normal vectors' angle

