# Welcome to 15618 Final Project: Parallel Augmented Reality with Planar Homography
Jiayu Bai, Xingsheng Wang

## Documents:
The pdf version of the project proposal can be found [here](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/project_proposal.pdf)

The checkpoint report can be found [here](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/15618Project_Midpoint_Report.pdf)

The final report can be found [here](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/15618FinalReport.pdf)

Image for feature matching can be found [here](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/cv_cover.jpg)

Source video files used are here: [1](https://youtu.be/K9sat26pMAw), [2](https://youtu.be/tLKyPBoIesA)

Final product for project is [here](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/ar.avi)

## Checkpoint:
At checkpoint, the parallelization is done on frame processing. There are a lot of frames in a video and using all the CPU threads, a portion of 
the frames are processed by each thread and output as a video segement. The segments are combined later to generate the final output.

## Final:
We achieve a final speedup of 45x with multiprocessing and CUDA acceleration.

## Example output:
![Example output](http://checkRaiseOnCloud.github.io/ParallelPlanarHomography/example_output.png)

