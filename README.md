# custom_pose_capture
Goal: Create 3D pose render from a single RGB Video file.
## Workflow:
Video->Detectron(2D Coordinates.npy)->VideoPose3D(3d joints.npy)->bvh_skeleton(.bvh)->(TODO)Blender(Render outut)
## How to Use it

1. clone this repository
2. Collab -> Open Notebook -> Github -> files -> file upload -> upload bvh_skeleton, utils and camera.h5 -> Run all cells -> Save output in bvh format
3. Import bvh file to blender & render(TODO)
## References
1. Detectron: https://github.com/facebookresearch/Detectron/
2. VideoPose3D: https://github.com/facebookresearch/VideoPose3D
3. bvh_skeleton: https://github.com/HW140701/VideoTo3dPoseAndBvh
4. HRM: https://github.com/Dene33/hmr/blob/master/csv_to_bvh.py
5. Render: https://github.com/Dene33/hmr/blob/master/csv_to_bvh.blend
