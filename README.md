# Render-3D-pose-from-a-video

Goal: Create 3D pose render from a single RGB Video file.
## Workflow:

Video->Detectron(2D Coordinates.npy)->VideoPose3D(3d joints.npy)->bvh_skeleton(.bvh)->Blender(Render outut)->(TODO)Custom mesh with animation
## How to Use it

1. clone this repository
2. Collab -> Open Notebook -> Github -> Run all cells -> Save output in bvh format
3. Import bvh file to blender & render.
4. Create a custom Mesh with rig to put that animation.(TODO)

## Preview 
![Input Video](https://github.com/lalasray/Render-3D-pose-from-a-video/blob/main/input.gif)

![BVH render in blender](https://github.com/lalasray/Render-3D-pose-from-a-video/blob/main/ouput.gif)
## References)


1. Detectron: https://github.com/facebookresearch/Detectron/
2. VideoPose3D: https://github.com/facebookresearch/VideoPose3D
3. bvh_skeleton: https://github.com/KevinLTT/video2bvh
4. Retarget BVH: http://diffeomorphic.blogspot.com/p/bvh-retargeter.html
5. Checkpoint: https://drive.google.com/file/d/1FSztcynGULFT7nkx6UIppIBy0dBwnmet/view?usp=sharing
