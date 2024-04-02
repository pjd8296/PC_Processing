# PC_Processing

### Loading the point cloud
The point cloud was loaded using Open3D library. It was then downsampled for faster processing for the rest of the code.

![newplot (1)](https://github.com/pjd8296/PC_Processing/assets/61617528/57e10dbd-d3e9-460d-940b-c41a1280d6b0)

### Aligned the point cloud to YZ-plane
The plane was detected and the rotation matrix was calculated using the rotation angle of the plane normal with X-axis (since equation of the plane YZ is `x=0`). Using this matrix, the point cloud was rotated to align with YZ plane. 

![newplot (2)](https://github.com/pjd8296/PC_Processing/assets/61617528/500a7d8a-6c96-43f8-a5c0-520b0bef3a09)

### Translated to align with the origin
Finally, the point cloud is translated so that centroid is aligned with the origin.

![newplot (5)](https://github.com/pjd8296/PC_Processing/assets/61617528/53daedd7-b2d5-4160-8f13-00cf179acd23)

### Converted it into mesh

![newplot (8)](https://github.com/pjd8296/PC_Processing/assets/61617528/76d04f73-0f45-4bd1-9a4a-a02aa055e962)

### Applied random transformation to the original point cloud

![newplot (11)](https://github.com/pjd8296/PC_Processing/assets/61617528/e462e7d9-8abb-4a36-972c-54bee404e7e4)

### Applied the orientation algorithm

![newplot (12)](https://github.com/pjd8296/PC_Processing/assets/61617528/b4a8127f-7a2b-43dc-a56e-9176c30b2384)

### Applied the translation algorithm

![newplot (13)](https://github.com/pjd8296/PC_Processing/assets/61617528/46997595-4531-4286-9d5a-68ef1533ec29)

### Finally converted it to mesh

![newplot (10)](https://github.com/pjd8296/PC_Processing/assets/61617528/dc187251-0a84-4bc7-8332-2641628dc956)
