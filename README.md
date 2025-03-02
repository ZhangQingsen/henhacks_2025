# henhacks_2025
repo for Qingsen Zhang for [henhacks 2025](https://www.henhackshackathon.com/)

### Idea
Single object 3D reconstruction from video

### Approach
SAM 2 + Gaussian Splatting

- ###### Phase 1:  
Using SAM 2 to segment video select objects
- ##### Phase 2:  
Using Gaussian Splatting for reconstruction

###### The original [SAM2](https://github.com/facebookresearch/sam2) and [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) repo are not included in this repo.

##### Plan
1. ✅ Utilize [Agent Laboratory](https://agentlaboratory.github.io/) to conduct literature review and plan formulation around the idea (Run on [Tencent Cloud](https://cloud.tencent.com/))
    - ✅ __1.1__ modify agent lab code to support deepseek-reasoner
    - ✅ __1.2__ modify angent lab code to remove other phases
    - ✅ __1.3__ modify agent lab code to save the prints into a .txt file
2. ❌ Create a user interface that allow __drag & drop__ of files and visualization of the process
    - __postpone after henhack 2025__
    - __2.1__ interface of drag & drop videos
    - __2.2__ interface of visualization the process of SAM 2 to select object
    - __2.3__ interface of visualize the process of reconstruction train
3. SAM 2 phase
    - make sure it run on provided video
    - ✅ perform the selection of object in video
4. Gaussian Splatting phase
    - make sure it run on provided video