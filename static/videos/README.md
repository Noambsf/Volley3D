Supplementary Material: Video Visualizations

This folder contains intermediate video visualizations.

1. Full Pipeline 3D Reconstruction 

- v_2Dnx8BpgUEs_c003_animated.mp4:
  Complete end-to-end 3D reconstruction on a monocular broadcast rally from 
  the SportsMOT test set, displaying synchronized 3D player meshes (SMPL) and 
  aerodynamic 3D ball trajectories in global court coordinates.

- match11_seq_22100_22395_animated.mp4
  Also a complete end-to-end 3D reconstruction on a different video.

NB : Kapwing was used to assemble both videos in a single one.

(* 2. Intermediate Sub-Module Visualizations

- v_2Dnx8BpgUEs_c003_tracks.mp4:
  Multi-object 2D tracking results (YOLOX + Deep-EIoU).

- v_2Dnx8BpgUEs_c003_calib.mp4:
  Continuous court keypoint detection and dynamic homography estimation (Maglo et al.).

- v_2Dnx8BpgUEs_c003_jump.mp4:
  Physics-informed jump spotting and aerial phase temporal boundaries (PoseConvSpot).

- v_2Dnx8BpgUEs_c003_wham.mp4:
  Reprojected 3D SMPL player meshes and body joints overlaid on the 2D broadcast (WHAM).

- v_2Dnx8BpgUEs_c003_ball.mp4:
  Composite visualization of the ball pipeline, showing 2D ball tracking, 
  temporal trajectory segmentation (TCN), and heuristic collision agent assignment.

- match11_seq_22100_22395_ball.mp4:
  Same visualization type but for a different video (the same one than in 1.). *)


2. Physics-Based 3D Ball Lifting & Baseline Comparisons (on VolliQ Dataset)

- rally_0009_gt_vs_ballistic_vs_drag.mp4:
  Ablation comparing Ground Truth, pure ballistics (no drag), and our drag-aware 
  aerodynamic model in 3D court space.

- rally_0009_reproj2d_3d_gt_vs_drag_vs_monotrack.mp4:
  Side-by-side comparison showing 2D reprojections (left) and metric 3D 
  trajectories (right) across Ground Truth, MonoTrack, and our proposed method.

- rally_0012_reproj2d_3d_gt_drag_monotrack.mp4:
  Same visualization type but on a shorter rally (corresponding to Figure 4 
  in the main paper).
