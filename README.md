# bilibili-cheese-downloader 哔哩哔哩课程下载器
哔哩哔哩课程下载器 / bilibili cheeses downloader 下载你已购买的或免费的 bilibili 课程。  
使用方式：下载 bdownloader.py 后运行即可。通过 bilibili-api 进行登录操作，通过手机app扫码完成登录，随后输入你已拥有的课程 ID 即可完成下载操作。  
注意：通过 ffmpeg 进行音视频合成操作，所以请提前配置好环境变量或将其复制到主程序同级目录下。  
所需依赖；  
pip install qrcode tk tqdm bs4 requests bilibili-api-python aiohttp  
