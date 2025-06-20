### Install BlockBench
First, we uses **BlockBench model file (.bbmodel)** to make a model.  
you can download BlockBench [here](https://www.blockbench.net/downloads).  
Since we follow BlockBench modeling, you should check [how to modeling and animating](https://www.blockbench.net/wiki/guides/bedrock-modeling).

### Create model
![1](https://github.com/user-attachments/assets/d183a96a-b644-4be4-af52-3f2fb5e06ead)  
First, you should generate your model as **generic model**.  
![2](https://github.com/user-attachments/assets/711cb24f-7fba-4687-8ee3-a54195835388)  
You can create your own model by using **cube** (mesh is not supported).

- If your client version is **1.21.3 or less**, cube rotation will be limited. (-45, -22.5, 0, 22.5, 45 degrees with only one axis)
- If your client version is **1.21.4 or more**, cube with any rotation can be rendered.

### Create model bone
![3](https://github.com/user-attachments/assets/53dfce65-edea-412f-b770-33782885800f)  
Model bone means **some group of cube**.
- All elements will be rendered as one item display packet per one model bone.
- Model bone can be freely rotated.
- BlockBench supports **animating model** per each model bone.

### Bone tag
![4](https://github.com/user-attachments/assets/2d315f38-cef9-4e3f-b896-3ba5cd093502)  
There's some built-in bone tag in BetterModel.

- **h_** - This model bone follows base entity's head rotation.
- **b_**, **ob_** or **hitbox** - This model bone uses world position hit box.
- **p_** - This bone can be mounted.

### Import model
First, put your model file to **plugins/BetterModel/models**.  
Second, execute reload to command **/bettermodel reload**.  
Third, apply generated resource pack in **plugins/BetterModel/build**.  
![5](https://github.com/user-attachments/assets/26e79e42-d2af-42db-b068-983aefafebc7)  
Done!
