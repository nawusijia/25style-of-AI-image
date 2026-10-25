# 25 种画风 × 6 个图片模型

娜乌斯嘉AI 的图片模型画风横评（第二轮）。同一道题、同一段提示词，看 Midjourney V8.2、GPT Image 2、Nano Banana Pro、Seedream 5.0 Pro、FLUX 2 Max、Luma uni-1 Max 在 25 种画风上各自画成什么样。

**怎么看：** 点右上角 Code → Download ZIP，解压后双击 `index.html` 就能在浏览器里看。

## 里面有什么

- `index.html`：对照网页。每种画风 6 张图并排，带模型名、完整提示词和娜娜的评分；点图看大图；有「盲测模式」可以先自己猜。
- `sheets/`：每种画风一张带模型名的对照大图，方便保存和转发。
- `images/full/`：150 张主对照图（长边 2048，JPEG）；`images/thumb/` 是网页用的缩略图。
- `assets/data.json`：全部题目、提示词、模型、评分的数据。

## 怎么测的

- 每种画风配一个适合它的题材（比如水墨画江南水村、像素画雨夜公交站）。同一题，六个模型用同一段提示词、同一画幅。
- 不用参考图、不加个人风格码、不做后期；所有瑕疵和跑画风都原样保留。
- Midjourney 走 LibTV 的 V8.2 入口（mj-v8.2，stylize 100 / weird 0 / chaos 0），每题出 4 张，固定取第 1 张参加对照。其余五家在 Lovart 上调用。
- 「很喜欢 / 可以用」是娜娜在匿名状态下的个人评分，只代表她一个人的口味。

## 速查：每种画风娜娜最喜欢的

| 编号 | 画风 | 娜娜很喜欢 | 对照图 |
|---|---|---|---|
| 01 | 自然纪实摄影 | GPT Image 2 | [对照大图](sheets/01-自然纪实摄影.jpg) |
| 02 | 高级时尚大片 | FLUX 2 Max | [对照大图](sheets/02-高级时尚大片.jpg) |
| 03 | 电影叙事剧照 | — | [对照大图](sheets/03-电影叙事剧照.jpg) |
| 04 | 复古胶片摄影 | Seedream 5.0 Pro | [对照大图](sheets/04-复古胶片摄影.jpg) |
| 05 | 超现实商业摄影 | — | [对照大图](sheets/05-超现实商业摄影.jpg) |
| 06 | 电影级写实CG | Midjourney V8.2 | [对照大图](sheets/06-电影级写实CG.jpg) |
| 07 | 风格化3D动画 | — | [对照大图](sheets/07-风格化3D动画.jpg) |
| 08 | 黏土定格 | — | [对照大图](sheets/08-黏土定格.jpg) |
| 09 | 纸艺立体场景 | Midjourney V8.2 | [对照大图](sheets/09-纸艺立体场景.jpg) |
| 10 | 等距低多边形 | Midjourney V8.2 | [对照大图](sheets/10-等距低多边形.jpg) |
| 11 | 日系赛璐璐动画 | Seedream 5.0 Pro | [对照大图](sheets/11-日系赛璐璐动画.jpg) |
| 12 | 日系厚涂游戏插画 | Midjourney V8.2 | [对照大图](sheets/12-日系厚涂游戏插画.jpg) |
| 13 | 美式漫画 | FLUX 2 Max | [对照大图](sheets/13-美式漫画.jpg) |
| 14 | 欧式绘本 | Nano Banana Pro | [对照大图](sheets/14-欧式绘本.jpg) |
| 15 | 平面商业插画 | GPT Image 2 | [对照大图](sheets/15-平面商业插画.jpg) |
| 16 | 古典油画 | Nano Banana Pro | [对照大图](sheets/16-古典油画.jpg) |
| 17 | 印象派油画 | — | [对照大图](sheets/17-印象派油画.jpg) |
| 18 | 透明水彩 | — | [对照大图](sheets/18-透明水彩.jpg) |
| 19 | 水粉／不透明水彩 | — | [对照大图](sheets/19-水粉-不透明水彩.jpg) |
| 20 | 木刻／套色版画 | — | [对照大图](sheets/20-木刻-套色版画.jpg) |
| 21 | 中国水墨写意 | Midjourney V8.2 | [对照大图](sheets/21-中国水墨写意.jpg) |
| 22 | 工笔重彩 | Luma uni-1 Max | [对照大图](sheets/22-工笔重彩.jpg) |
| 23 | 浮世绘 | — | [对照大图](sheets/23-浮世绘.jpg) |
| 24 | 新艺术装饰风格 | Luma uni-1 Max | [对照大图](sheets/24-新艺术装饰风格.jpg) |
| 25 | 像素艺术 | — | [对照大图](sheets/25-像素艺术.jpg) |

## 署名

跑图：洄光（GPT）；网页与视频包装：克肆（Claude）；评分：娜娜。视频在抖音 / 小红书 / B站搜「娜乌斯嘉AI」。

标题字体为缝合像素字体 Fusion Pixel，SIL Open Font License 1.1，见 `assets/FusionPixel-OFL.txt`。
