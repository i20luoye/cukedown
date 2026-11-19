# CukeDown — Online 4K Video & Original Image Downloader (Watermark-Free)

**Live Website**: [https://cuke.io](https://cuke.io) (中文) · [https://cuke.io/en/](https://cuke.io/en/) (English) · [Guides / 使用教程](https://cuke.io/guides)

CukeDown is a clean, ad-free, login-free online media extraction workbench built to solve the #1 frustration with web downloaders: **quietly handing out blurry 360P / 576P preview streams instead of the true highest-quality original source.**

---

## Key Highlights

- **Highest Quality Queued First**: Decouples instant preview playback from master downloads. Automatically prioritizes **4K / 2K / 1080P** video streams (with lossless server-side audio+video muxing for DASH sources) while exposing the full quality ladder and standalone audio tracks.
- **Zero Login & Zero Ad Popups**: Paste any public share link directly—no registration walls, no browser extensions, no fake download buttons, and no personal platform cookies required.
- **Fair Free Tier (Never Hard-Blocked)**: Daily full-speed original-quality quota for anonymous visitors (failed parses never deduct quota), automatically falling back to an unlimited free standard-speed lane instead of throwing a hard paywall.
- **Built-in Post-Processing**: Trim long videos by exact `start` / `end` timestamps without downloading the full file, convert clips into crisp two-pass palette GIFs, package Apple Live Photos (`JPG + MOV`), extract standalone MP3 audio, and copy original post captions.

---

## Verified Platform Support Matrix

| Platform | Verified Max Quality | Watermark & Format Handling | Direct Tool Page |
| :--- | :--- | :--- | :--- |
| **YouTube** | `2160P 4K` / `1440P` / `1080P60` | Lossless DASH video + audio mux to MP4, MP3 audio & timestamp clip | [cuke.io/en/youtube](https://cuke.io/en/youtube) |
| **TikTok** | `1080P HD` | Watermark-free video & photo slideshows (zero-cookie fallback for gated posts) | [cuke.io/en/tiktok](https://cuke.io/en/tiktok) |
| **Instagram** | `1440P 2K` / `1080P` | Reels HD mux + instant progressive MP4 + full multi-photo carousels | [cuke.io/en/instagram](https://cuke.io/en/instagram) |
| **Douyin (抖音)** | `1080P` Original (`H.264` / `H.265`) | Bypasses 576P web preview; extracts photo albums, Live Photos & native BGM | [cuke.io/douyin](https://cuke.io/douyin) |
| **RedNote / Xiaohongshu (小红书)** | Uncompressed `PNG` / `JPG` + HD Video | Direct CDN original resolution + one-click full-post ZIP + Apple Live Photos | [cuke.io/xiaohongshu](https://cuke.io/xiaohongshu) |
| **WeChat Channels (微信视频号)** | Original HD `MP4` | Paste public `weixin.qq.com/sph/...` link, auto Isaac64 stream decrypt | [cuke.io/wechat-channels](https://cuke.io/wechat-channels) |
| **Bilibili (B站)** | `4K` / `1080P60` / `1080P` | Full DASH resolution ladder, `b23.tv` short links, `?p=` episodes & audio | [cuke.io/bilibili](https://cuke.io/bilibili) |
| **X (Twitter) / Threads** | Original HD `MP4` / Full-Res Images | Highest-bitrate MP4, GIF animations & full-size photos | [cuke.io/en/x](https://cuke.io/en/x) |
| **Pinterest / Pixiv** | Full Original Resolution | Pin HD MP4, Pixiv full-size illustrations & Ugoira to GIF / MP4 | [cuke.io/en/pixiv-download](https://cuke.io/en/pixiv-download) |

---

## 中文简介

**CukeDown**（[https://cuke.io](https://cuke.io)）是一个免登录、无弹窗广告的全网无水印视频与无损原图在线解析下载工作台：

- **默认最高画质优先入队**：抖音跳过 576P 模糊预览流直出 1080P 原画，YouTube / B站默认锁定 4K / 1080P 服务端无损音画合并，Instagram Reels 最高 2K / 1080P，小红书直出未压缩原图并支持整篇一键 ZIP 打包。
- **微信视频号免抓包**：公开 `weixin.qq.com/sph/...` 分享链接直接粘贴，自动完成流式解密输出标准可播放 MP4；首页下方亦提供本地加密缓存前 128KB 无损解密工具。
- **实用转换一站集成**：支持超长视频按起止时间在线截取片段、两步调色板高清 GIF 制作、iPhone 实况照片（`JPG + MOV`）打包与独立 MP3 提取。
- **30 篇平台实测教程**：[https://cuke.io/guides](https://cuke.io/guides)（涵盖抖音去水印画质原理、小红书原图与链接过期处理、微信视频号下载、实况照片与 GIF 参数建议等）。

---

## Feedback & Bug Reports

This repository serves as the public documentation and issue tracker for **CukeDown** (`cuke.io`).  
If a public link fails to parse or misses a higher resolution tier, please open an issue with the platform name and link format so we can investigate and improve compatibility.

> **Disclaimer**: CukeDown is intended strictly for personal study, research, and lawful archiving. All media copyrights belong to their original creators and platforms.
