# TensorFlow Environment
## I am going to share the step-by-step process of installing TensorFlow on your laptop.
# Installation of TensorFlow Environment

## Before you can get started developing deep-learning applications, you need to set up your workstation. It’s highly recommended, although not strictly necessary, that you run deep- learning code on a modern NVIDIA GPU
## If you don’t want to install a GPU on your machine, you can alternatively consider running your experiments on an AWS EC2 GPU instance or on Google Cloud Platform. But note that cloud GPU instances can become expensive over time.

## Step- 1:
### Create a folder that used to contain the projects or code of your application or project. It's better to create this folder on the _C drive_.
### Open the Windows File Explorer. Navigate to C drive-> Users-> Your_users (C:/Users/Your_users).
## Step- 2: 
### Open the folder that you created in the C drive users and then navigate to the "TensorFlow" folder. Open the TensorFlow folder and apply _Shift + RightClick_. Select the option _Power-Shell_.
![Image](https://github.com/user-attachments/assets/f446e216-66fb-4db2-8fa4-ef3d315ba0be)
## Step- 3:
### Before you create a TensorFlow environment, please check whether Python is installed on your desktop. If it is installed, then check for Python on your desktop through the Command Line.
![Image](https://github.com/user-attachments/assets/0316ad41-48d5-4906-b8d1-a64cc9b9531d)

### Open the Command Line and type _py_ or _python_. These commands were used to execute Python in the Command Line.
## Step- 4: 
### Create the TensorFlow environment by using the command:
# _python -m venv <your_env_name>_ or py -m venv <your_env_name> (This command will create a structure or skeleton of the environment)
![Image](https://github.com/user-attachments/assets/156d888c-ba38-49b6-81fc-428504779e97)
### Apply this command in PowerShell; the path must be in _C:/users/your_users/TensorFlow_Folder_.
## Step -5: 
### Activate the environment. To activate the environment by applying the command in PowerShell:
#  _./<your_env_name>/Scripts/activate_.
![Image](https://github.com/user-attachments/assets/be93c9ca-57fd-467a-a295-b17a1e2c6aba)
## Step- 6:
### Create a Jupyter kernel for identifying TensorFlow. Install the Jupyter Kernel by using the command:
# _pip install ipykernel_.
![Image](https://github.com/user-attachments/assets/55df8135-3a85-4d23-90d6-d25aa0406ad7) 
### Install the required dependencies using the PIP command for TensorFlow.
# _pip install tensorflow_.
![Image](https://github.com/user-attachments/assets/3b8d9b62-d1ec-4f95-a379-a9532871c62a)
## step- 7:
### Create a name for the kernel that you have created by using this command:
# _python -m ipykernel install --user --name=<kernel_name>_ or _py -m ipykernel install --user --name=<kernel_name>_.
![Image](https://github.com/user-attachments/assets/b9ca9fc6-70ca-4bbf-bf84-310dfbd56f57)
