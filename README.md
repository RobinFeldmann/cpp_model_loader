# How to use

get latest libtorch 

mkdir build 

cd build

cmake -DCMAKE_PREFIX_PATH=/path/to/libtorch ..

cmake --build . --config Release

./loader model_0.pt

