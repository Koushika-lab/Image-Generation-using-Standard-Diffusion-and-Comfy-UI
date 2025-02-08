# Image-Generation-using-Standard-Diffusion-and-Comfy-UI
Installation and Implementation:
The easiest way to install ComfyUI on Windows is by using the standalone installer available on the official releases page. This version includes all the necessary dependencies, such as PyTorch, Hugging Face Transformers, and CUDA libraries, eliminating the need for separate installations. It provides a hassle-free setup, making it the best option for beginners and advanced users alike.
Steps to Install ComfyUI on Windows
1.	Download the latest standalone version of ComfyUI from the official releases page or a trusted source.
2.	Extract the downloaded comfyui-windows.zip file using 7-Zip or WinRAR.
3.	Add models to the appropriate directory (e.g., models/checkpoints for Stable Diffusion models).
4.	Run run_cpu.bat (for Windows with CPU) to start ComfyUI.
         ![image](https://github.com/user-attachments/assets/340daec8-13e3-488e-ae39-20e7d80ba1f7)
				Fig (a) Comfy UI zip file contents
5.	You need a checkpoint model to start using ComfyUI. Download a checkpoint model from the Hugging Face website. Put the model in the folder:
ComfyUI_windows_portable\ComfyUI\models\checkpoints
Note: You also can share models with other Stable Diffusion GUI such as AUTOMATIC1111.
     ![image](https://github.com/user-attachments/assets/ba2d0a97-dcf8-4e16-9541-6c9550bda649)

			Fig (b) Navigating to checkpoints
6.	Now simply run the run_nvidia_gpu.bat (recommended) or run_cpu.bat. ComfyUI should automatically start on your browser. The command line will execute and generate a URL http://127.0.0.1:8188/ that you can now open in your browser.

When you launch ComfyUI, the default workflow graph will load, which is designed to work with any Stable Diffusion model. You can select a model using the Load Checkpoint node, which will display all the models you have downloaded and placed in the checkpoints folder.
To generate images, simply click on Queue Prompt, and the system will process the request. The generated images will be saved in the ComfyUI/outputs folder for easy access.
