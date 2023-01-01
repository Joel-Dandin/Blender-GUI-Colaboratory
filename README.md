# blender-GUI-colab

<a href="https://colab.research.google.com/github/Joel-Dandin/blender-GUI-colab/blob/main/Blender%20in%20Colab.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This is a Python script that allows you to use Blender 3.0+ and older version using Google Colaboratory.
The blender application can be found in the applcation menu or u can directly start the application from /content/<version name>/blender

## Steps

1. Add a username and password in the Create User step.
2. Go to [remotedesktop.google.com/headless](https://remotedesktop.google.com/headless)
3. Press Begin in "Set up another computer."
4. Press Next, then Authorize.
5. Copy and paste the link for Debian Linux in the Installation Process of the colab file.
![link](https://user-images.githubusercontent.com/60149879/210169909-0e824797-8fb2-40a5-8697-f4d70a8c36e7.png)
6. Run the remaining codes to install Blender.
7. You can access the Colab GUI from the remote access panel [remotedesktop.google.com/access](https://remotedesktop.google.com/access) the password is the password set during the Installation Process stage.

## Images

![image](https://user-images.githubusercontent.com/60149879/210170352-9a9961c4-daad-4433-828b-8f22be7f6334.png)

![image](https://user-images.githubusercontent.com/60149879/210170544-53b3d452-29d7-4f05-b25a-5df2ed54740f.png)

### A few notes
1. You must own a Google account.
2. Use this script only to create blender models use this script to render the scenes.
2. One notebook can only run for maximum time of 12 hours (24 hours for Google Colab Pro) but not guaranteed.
3. EEVEE rendering is not supported in a virtual machine.
4. This script is not tested fully yet. Expect some errors.
5. Do note that your access to GPU may be limited or blocked if you render for many hours.
6. This script is intended for those who have no access to high-end GPU for rendering. Please use them responsibly!

## FAQ
### An error occured!
Check which section of the code failed and identify the error (such as misspelled files or link). If you don't understand the error, try re-running the code with the play button at the side. If it still fails, go to `Runtime > Restart and run all` to restart the code or try `Runtime > Factory reset runtime`. If all else fails, open an issue in GitHub with the error log you encountered attached and the details of your setup.

## Disclaimer
Google Colab is targeted to researchers and students to run AI/ML tasks, data analysis and education, not rendering 3D scenes. Because the computing power provided are free, the usage limits, idle timeouts and speed of the rendering may varies time by time. [Colab Pro and Colab Pro+](https://colab.research.google.com/signup) are available for those who wanted to have more powerful GPU and longer runtimes for rendering. See the [FAQ](https://research.google.com/colaboratory/faq.html) for more info. In some cases, it might be faster to use an online Blender renderfarm.
