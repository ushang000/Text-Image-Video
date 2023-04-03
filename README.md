# Text-Image-Video
在google colab里实现文字转图片和视频

用Colab免费部署自己的AI绘画云平台—— Stable Diffusion

Text To Image
https://colab.research.google.com/drive/1PVfr7X0eKD1CCEi4xamLeDYyTCO9VVOW#scrollTo=vDflx4IKH7Il



Text To Video
https://colab.research.google.com/drive/1Mga07Z5yPRtIMuYyeTb3QyUzdK4omUhx#scrollTo=RfcIogNetLYl

进入链接后点击右上角的连接按钮
![image](https://user-images.githubusercontent.com/7991891/229448114-82e54dde-df36-425f-aa5d-54948b641d44.png)

点击确定

![image](https://user-images.githubusercontent.com/7991891/229448921-fa05be61-cf16-42b4-bc67-0e0d8948884c.png)

然后运行第一个脚本

![image](https://user-images.githubusercontent.com/7991891/229455376-d5b1e6f8-d6c4-4c93-8265-87eda89bde75.png)

查看当前使用的机器。一般是从 K80、T4、P100、V100 中随机分配一个。

安装对应的库

![image](https://user-images.githubusercontent.com/7991891/229449566-ccc3b554-4eb2-4b94-929c-e41caa62785e.png)

设置token（可以忽略）

![image](https://user-images.githubusercontent.com/7991891/229449771-8b1ce608-4a0e-4a65-960e-e643b4992738.png)

这个要去Hugging Face. 注册账号，然后申请个自己的token，https://huggingface.co/settings/tokens

![image](https://user-images.githubusercontent.com/7991891/229450737-c90a61f6-0ceb-4a0a-90f5-8c6087d54eab.png)

拉取模型

![image](https://user-images.githubusercontent.com/7991891/229450949-397a21bd-9dcb-4bca-a3f3-cae79c412732.png)

也可以在HuggingFace Hub上自己找个对应的模型

![image](https://user-images.githubusercontent.com/7991891/229453242-e98c7552-5cb8-4df8-a794-00eab5963fff.png)

接下来就可以运行代码了，输入一段英文描述，就可以生成对应的图片了。

![image](https://user-images.githubusercontent.com/7991891/229454620-eee03a11-3fcb-42f5-a0f5-e36b44d0fdf6.png)



