<h1 align="center">DownEdit</h1>

![Static Badge](https://img.shields.io/badge/python-3.8%2B-brightgreen)

<p>DownEdit is a powerful program that allows you to download videos from various social media platforms such as TikTok, Douyin, Kuaishou, and more. With DownEdit, you can easily download videos from user profiles and edit them in bulk. You have the option to flip the videos horizontally or vertically throughout the entire directory with just a single click. Stay tuned for more exciting features coming soon!</p>

## ✨ Preview
<p align="center">
  <img src="https://github.com/sokunheng/DownEdit/assets/44894784/d48f25d4-17ea-47ea-b5df-df8c411ba542.gif" alt="animated" />
</p>

## 🔥 Current Features
- `Edit Video`: Enhance videos with versatile functions across entire directories.
- `Edit Photo`: Quickly enhance images in bulk with various functions in bulk.
- `Download all videos`: Retrieve videos from users (TikTok, Kuaishou, Douyin, etc.) without watermarks.
- `Bulk AI Generator`: Process images and videos in bulk using powerful generative AI.
- `AI Editor`: Transform your visual content effortlessly with an AI editor designed for both images and videos.

## 🌐 Service

| Website| Provider| Single Video | User's Videos | Stream | Status | Auth Required|
| --- | --- | --- | --- | --- | --- | --- |
| [tiktok.com](https://www.tiktok.com/) | `None` | ✔️ | ✔️ | ✔️ | ![Active](https://img.shields.io/badge/Active-brightgreen) | ❌ |
| [douyin.com](https://www.douyin.com/) | `None` | ✔️ | ✔️ | ✔️ | ![Inactive](https://img.shields.io/badge/Inactive-red) | ✔️ |
| [kuaishou.com](https://www.kuaishou.com/?isHome=1) | `None` | ✔️ | ✔️ | ✔️ | ![Inactive](https://img.shields.io/badge/Inactive-red) | ✔️ |

## 🤖 AI
| Type | Model | Param | Provider| Minimal | Bulk | API | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Image | `Stable-diffusion` `Midjourney` | 137B | Enterpix | ✔️ | ✔️ | ✔️ | ![Active](https://img.shields.io/badge/Active-brightgreen) |
| Image | `DownEditNet` |  | DownEdit | ✔️ | ✔️ | ❌ | ![Active](https://img.shields.io/badge/Active-brightgreen) |


## 🚀 Usage
- **`Edit Video`** - Simply copy and paste (right click) whatever directory location you would like to process.

<details>
<summary>Tutorial</summary>

```html
Enter Folder: C:\Users\Name\Desktop\Folder\Video
```

![Edit_Video_AdobeExpress](https://user-images.githubusercontent.com/44894784/200826802-58b223ea-dd01-4f3a-b896-d87228cddd4e.gif)



 Change it according to your desired video speed.
```html
Select Speed: 1.2 or 2 
```

 Input your music file location
```html
Enter Music: C:\Users\Name\Desktop\Folder\music_name.mp3
```
```html
Enter Music: music_name.mp3
```
 

</details>


- **`Download douyin videos`** - Download all video from user by input user link.

<details>
<summary>Tutorial</summary>

```html
Enter User Link: https://www.douyin.com/user/MS4wLjABAAAAzknqQznbR4gNJFBtYQE8ptAbM4Djr8bGDdfCUataDVSfQK8YMkSI8J5v
```
 <img src="https://user-images.githubusercontent.com/44894784/200826881-0051ef41-a59a-4b39-ae01-d252dc796acc.gif" alt="animated"  width="640"/>

</details>

- **`Download tiktok videos`** - Download all video from user by input username with @.

<details>
<summary>Tutorial</summary>

```html
Enter User: @tiktok
```
<img src="https://user-images.githubusercontent.com/44894784/200826983-a45fc5d0-343a-4921-9077-6f97ebca67a8.gif" alt="animated"  width="640"/>

</details>

- **`Download kuaishou videos`** - Remember to input your own **Cookie**. Otherwise it won't work.

<details>
<summary>Tutorial</summary>

-----

 Step 1. Right click and select on Inspect element.
  
<img src="https://user-images.githubusercontent.com/44894784/200830971-90ee9df9-4b7d-4648-a6a0-0ac327dd9ac7.jpg" alt="tutorial"  width="640"/>

-----
  
```html
Input Cookie: kpf=PC_WEB; kpn=KUAISHOU_VISION; clientid=3; did=web_dfe556cf2a809f194bf54a1d5125ad31; didv=1667716807591; _bl_uid=2bl0haaF5Fnfjd5Ft0tXkm0ksz17; client_key=65890b29; userId=3114192403; ktrace-context=1|MS43NjQ1ODM2OTgyODY2OTgyLjI2NzI4OTgxLjE2NjgwOTQzMTUzNzQuMjM3MDQw|MS43NjQ1ODM2OTgyODY2OTgyLjM5ODM1Mzg4LjE2NjgwOTQzMTUzNzQuMjM3MDQx|0|graphql-server|webservice|false|NA; kuaishou.server.web_st=ChZrdWFpc2hvdS5zZXJ2ZXIud2ViLnN0EqAB8CBZs_S_PC_PFDJL2Do4j19XodeBMi9XmTD_kxJalX8oHZtLxNadJ2HpJKDvkuyRCU52pxMA7ulFKo32pyr3PO4phQTmcghw3M1pjL6gCVW5KyVSo-nJMvTcXhpDn501B6Yz0-XbxYHTdWZw7ITl-lgpWwO_hYalq68Wt5Q7ut7iEPGAVjIXH-r-y5DteaqG1ocz5k0PH3QMaqQSytJN5xoS-1Rj5-IBBNoxoIePYcxZFs4oIiBVPhNOHXk5SvSU1kq6lB8hpXv9CiiIqe6gJihLWZAsVCgFMAE; kuaishou.server.web_ph=8b579bf7ba4c2f740ca6486d022008b01ed1
```
  
Step 2. Copy your Cookie browser.
  
<img src="https://user-images.githubusercontent.com/44894784/201191235-1abda841-7ae1-4bef-a06a-b7c06d12c927.jpg" alt="tutorial"  width="640"/>

-----  
  
```html
Enter User ID: 3xnpgvvuei3umwk
```
  
Step 3. Copy user ID you want to download.  

<img src="https://user-images.githubusercontent.com/44894784/200831086-9e880d15-6921-4593-a46a-c9462e58cd5e.jpg" alt="tutorial"  width="640"/>
  
-----  
  
Tips: If you still getting error, try changing your Browser, use Incognito/Private mode and reset your Internet/IP.

</details>

- **`Edit Photo`** - Simply copy and paste (right click) whatever directory location you would like to process.

<details>
<summary>Tutorial</summary>
  
  - `Remove Background AI`
<img src="https://github.com/sokunheng/DownEdit/assets/44894784/2f351ebc-1dc2-4d97-b26f-2218426a7969.png" alt="down_edit_photo" width="537" />
  
</details>

## 🔎 Requirements
- Python 3.8 or better

## ⚙ Installation 
Step 1. Download and install [python](https://www.python.org/downloads/) on your pc.
```html
https://www.python.org/downloads/
```
Step 2. Click <u>install.bat<u> for automatic python libraries installation
```html
 install.bat
```
Step 3. Run the script
```ht
 main.py
```
-----
If you're a non coder, you can also download the application and use it on your Window without installing python. [Download here.](https://github.com/SokunHeng/DownEdit/releases)

**Additional**: Install the Microsoft [Cascadia](https://github.com/microsoft/cascadia-code) font on your computer if your terminal does not support the font, which is resulting in program error.

## 🔨 Module
  
  <details>
<summary>List</summary>
    
- [Moviepy](https://github.com/Zulko/moviepy)
- [Inquirer](https://pypi.org/project/inquirer/)
- [Colorama](https://github.com/tartley/colorama)
- [Rich](https://github.com/Textualize/rich)
- [Requests](https://requests.readthedocs.io/en/latest/)
- [Pystyle](https://github.com/billythegoat356/pystyle)
- [Request_HTML](https://github.com/kennethreitz/requests-html)
- [Random_User_Agent](https://pypi.org/project/requests-random-user-agent/)
- [Pillow](https://github.com/python-pillow/Pillow)
- [Gdown](https://github.com/wkentaro/gdown)
- [Torch](https://pypi.org/project/torch/)

</details>

## Author

👤 **Sokun Heng**

- Github: [@SokunHeng](https://github.com/SokunHeng)


## Show your support

Please ⭐️ this repository if this project helped you!


## 📝 License
Copyright © 2022 [SokunHeng](https://github.com/SokunHeng).<br />
