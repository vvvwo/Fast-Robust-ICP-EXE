# Fast-Robust-ICP-EXE

The executable is compiled from the project：Fast-Robust-ICP，proposed by Prof. Zhang Juyong.

![registration](https://user-images.githubusercontent.com/65271555/179463083-f86615f7-3413-494a-bb73-0aa8f52f7a36.jpg)

Project Link: https://github.com/yaoyx689/Fast-Robust-ICP

## Usage

Download the exe file and run the code by "start.bat"

Instanece: FRICP.exe target.ply source.ply res/ 3

The input parameters:

1. an input file storing the source point cloud;
2. an input file storing the target point cloud;
3. an output path storing the registered source point cloud and transformation;
4. registration method:
```
0: ICP
1: AA-ICP
2: Ours (Fast ICP)
3: Ours (Robust ICP)
4: ICP Point-to-plane
5: Our (Robust ICP point-to-plane)
6: Sparse ICP
7: Sparse ICP point-to-plane
```

## Citation

Please cite the following papers if it helps your research:
```
  @article{zhang2021fast,
    author={Juyong Zhang and Yuxin Yao and Bailin Deng},
    title={Fast and Robust Iterative Closest Point}, 
    journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
    year={2021},
    volume={},
    number={},
    pages={1-1}}
```
