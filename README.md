# playground-v2.5-webui
要想把项目启动起来就跟把大象装进冰箱一样，总共分三步：

## 第一步，下载playground v2.5的diffusers格式的模型
下载地址：https://huggingface.co/playgroundai/playground-v2.5-1024px-aesthetic

## 第二步，安装环境
1、直接安装

pip install -r requirements -i https://mirrors.aliyun.com/pypi/simple/

2、diffusers库要求 >=0.27.0，目前还没有上正式版本，所以需要直接安装dev版本

pip install git+https://github.com/huggingface/diffusers.git

pip install transformers accelerate safetensors

## 第三步，clone这个项目到本地
直接执行：python app.py

注：如需使用api，可以直接增加启动参数 --api 即可

注意：功能只是简版，不完善！

