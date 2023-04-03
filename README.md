# Text-Image-Video
在google colab里实现文字转图片和视频

用Colab免费部署自己的AI绘画云平台—— Stable Diffusion

文字生成图片：

Text To Image
https://colab.research.google.com/drive/1PVfr7X0eKD1CCEi4xamLeDYyTCO9VVOW#scrollTo=vDflx4IKH7Il


进入链接后点击右上角的连接按钮
![image](https://user-images.githubusercontent.com/7991891/229448114-82e54dde-df36-425f-aa5d-54948b641d44.png)

点击确定

![image](https://user-images.githubusercontent.com/7991891/229448921-fa05be61-cf16-42b4-bc67-0e0d8948884c.png)

然后运行第一个脚本

![image](https://user-images.githubusercontent.com/7991891/229455376-d5b1e6f8-d6c4-4c93-8265-87eda89bde75.png)

查看当前使用的机器。一般是从 K80、T4、P100、V100 中随机分配一个。如果你分到的是V100，那么恭喜你，放个鞭炮庆祝下。

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


文字生成视频：

Text To Video
https://colab.research.google.com/drive/1Mga07Z5yPRtIMuYyeTb3QyUzdK4omUhx#scrollTo=RfcIogNetLYl

点击上面链接进入，运行方式跟文字生成图片的一样。

拉取模型

![image](https://user-images.githubusercontent.com/7991891/229456401-cdaa5bb8-49de-415d-8134-97b3fa2a1d01.png)

模型地址

![image](https://user-images.githubusercontent.com/7991891/229456680-e9236714-07db-4607-96e5-529ae71c102c.png)

最后是生成视频代码及效果

![image](https://user-images.githubusercontent.com/7991891/229457052-298cd810-010d-44f5-b568-d2835e86846c.png)

![image](https://user-images.githubusercontent.com/7991891/229457143-b936fb3b-2aed-4a03-804a-996d2072271b.png)

最后的最后，如果里面的代码和文本有更改，最好保存到云端硬盘上，方面查看修改记录，内容修改都是自动保存的，非常棒！
下次也可以直接从云端硬盘直接进入。
