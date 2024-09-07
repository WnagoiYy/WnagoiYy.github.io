---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)




我在做一个根据图片生成文字的功能，需要提供给大模型一个提示词模板用以根据图片生成文字，但是模板生成的文字和完美的文字描述有些差异，帮我优化修改一下提示词模板，达到能生成完美提示词的要求。

我的提示词模板是：请根据提供的图片生成详细的描述文字。图片应描述为[描述图片的总体风格，例如'极简数字插画'或'生动的油画']。使用位置和形容词描述元素或者颜色，如[背景处隐约可见抽象的城市建筑]。然后形容描述图片传达的情绪或氛围，如[宁静、充满活力、神秘等]。突出对比或细节，如[光影效果、阴影、纹理等]。

其中一幅画生成的提示词：一幅极简数字插画风格的图片。图片的背景是浅蓝色的天空，天空中散布着几朵白云。画面的左右两侧隐约可见抽象的城市建筑，建筑的轮廓和窗户以浅蓝色和白色为主，显得非常简洁和现代。画面的下方是一片深蓝色的区域，可能是水面或地面，与上方的浅蓝色天空形成了鲜明的对比。整体画面给人一种宁静、清新和现代的感觉，光影效果柔和，阴影和纹理处理得非常细腻。

完美的提示词：一幅极简风格的数字插画，画面中有一片明亮的蓝色天空，飘着柔和的云朵。背景处隐约可见抽象的城市建筑，构成了一幅宁静的城市风景。整幅作品的色彩清淡，强调了一种平静而乐观的氛围。图像的下半部分是一个平滑的蓝色渐变，与天空形成了微妙的对比。

修改后的提示词模板：



通义千问生成的提示词：一幅极简数字插画风格的图片。图片的背景是浅蓝色的天空，天空中散布着几朵白云。画面的左右两侧隐约可见抽象的城市建筑，建筑的轮廓和窗户以浅蓝色和白色为主，显得非常简洁和现代。画面的下方是一片深蓝色的区域，可能是水面或地面，与上方的浅蓝色天空形成了鲜明的对比。整体画面给人一种宁静、清新和现代的感觉，光影效果柔和，阴影和纹理处理得非常细腻。

完美的提示词：一幅极简风格的数字插画，画面中有一片明亮的蓝色天空，飘着柔和的云朵。背景处隐约可见抽象的城市建筑，构成了一幅宁静的城市风景。整幅作品的色彩清淡，强调了一种平静而乐观的氛围。图像的下半部分是一个平滑的蓝色渐变，与天空形成了微妙的对比。


用一句话概括图片内容，然后详细描述图片中的内容，包括物体、人物、动物以及图片的氛围和情绪。
图像描述结果
这是一幅描绘城市天际线的卡通插画。图片中，几栋高楼耸立在蓝色的天空下，楼房轮廓清晰，但细节很少。天空上飘着几朵白色的云彩，整体画面清新明快，透着一丝梦幻和美好。

A BDGE CF
DGBE A FC
GDEB FC A

https://github.com/jerryc127/hexo-theme-butterfly
https://github.com/solstice23/hexo-theme-argon

git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git themes/butterfly
升級方法：在主題目錄下，運行 git pull
npm install hexo-renderer-pug hexo-renderer-stylus --save

Hexo-butterfly评论系统配置: Gittalk_hexo butterfly免费评论-CSDN博客
https://blog.csdn.net/qq_33384402/article/details/107200465

推荐16个高清图片网站，可做网站背景_图片 高清 网站-CSDN博客
https://blog.csdn.net/qq_43925037/article/details/107310384

《你的名字。》 2K SDR 4K 原盘超采样壁纸 | Pil0tXia
https://www.pil0txia.com/post/2023-04-05_kimi-no-na-wa-wallpaper/

Butterfly 安裝文檔(一) 快速開始 | Butterfly
https://butterfly.js.org/posts/21cfbf15/

部署Hexo博客后台系统Qexo | InsectMk的个人空间
https://insectmk.cn/posts/637bb1fe/#%E7%94%A8%E6%88%B7%E9%85%8D%E7%BD%AE

Butterfly解决Gitalk密钥暴露的问题 | 你所不知道的物語;
https://www.hitagi.icu/posts/17b458ca/#%E9%97%AE%E9%A2%98%E5%88%86%E6%9E%90