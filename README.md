# SPlayer - 尚未完成

> 一个简约的在线音乐播放器，**项目尚未完成**，不保证可用性

## 🎉 功能

- 账号登录（ 目前仅支持扫码，更多登录方式待添加 ）
- 每日推荐歌曲与私人 FM
- 支持音乐云盘内歌曲播放
- 音乐渐入渐出
- MV 与视频播放
- 歌词滚动显示以及评论区功能
- 播放器音乐频谱显示（ 实验性功能，需在设置中开启 ）
- 明暗模式自动 / 手动切换
- 对移动端简单适配

## ⚙️ 部署

### API 服务

> 本程序依赖 [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) 运行，请确保您有该 API 地址

- 请在根目录下的 `.env` 文件中的 `VITE_MUSIC_API` 中填入 API 地址

```js
VITE_MUSIC_API = "your api url"
```

### 安装依赖

```bash
pnpm install
# 或者
yarn install
# 或者
npm install
```

### 开发

```bash
pnpm dev
# 或者
yarn dev
# 或者
npm dev
```

### 构建

```bash
pnpm build
# 或者
yarn build
# 或者
npm build
```

构建完成后可将生成的 `dist` 文件夹内的文件上传至服务器