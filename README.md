# Neon Hero (ネオン・ヒーロー)

**Neon Hero** is a browser-based rhythm action game with a vibrant cyberpunk aesthetic. Play with your favorite music from YouTube or local files!

**ネオン・ヒーロー**は、鮮やかなサイバーパンク・スタイルのブラウザベースのリズムアクションゲームです。YouTubeの動画やローカルの音楽ファイルを使って、お気に入りの曲で遊ぶことができます！

![Neon Hero Screenshot](https://via.placeholder.com/800x450?text=Neon+Hero+Gameplay) 
*(Screenshots coming soon / スクリーンショットは準備中です)*

## 🎮 Repository Info

*   **Repository Name:** `neon-hero`
*   **Description:** A browser-based cyberpunk rhythm game that generates charts from YouTube videos or local media files. (YouTubeの動画やローカルファイルから譜面を生成して遊べる、ブラウザベースのサイバーパンク風リズムゲーム。)

## 🚀 Live Demo (ライブデモ)

You can play Neon Hero live on GitHub Pages:
[https://dma-cmyk.github.io/neon-hero/](https://dma-cmyk.github.io/neon-hero/)

## ✨ Features (特徴)

*   **Dynamic Chart Generation:** Automatically generates note patterns based on the duration of the media.
*   **Multiple Media Sources:**
    *   **YouTube:** Paste a URL to play with any video.
    *   **Local Files:** Upload MP3 or MP4 files from your device.
*   **Cross-Platform:**
    *   **PC:** Play using keyboard arrow keys.
    *   **Mobile:** Touch controls optimized for smartphones.
*   **Neon Visuals:** Stylish glowing graphics and animations using HTML5 Canvas.
*   **Sharing:** Share your favorite YouTube tracks via URL parameters (e.g., `https://dma-cmyk.github.io/neon-hero/?v=VIDEO_ID`).

## 🕹️ How to Play (遊び方)

The goal is to hit the falling notes at the right timing as they reach the judgment line.
落ちてくるノーツが判定ラインに重なるタイミングで操作します。

### Controls (操作方法)

| Lane | PC (Keyboard) | Mobile (Touch) |
| :--- | :--- | :--- |
| **Left (左)** | `Left Arrow (←)` | Tap Left Button |
| **Down (下)** | `Down Arrow (↓)` | Tap Down Button |
| **Up (上)** | `Up Arrow (↑)` | Tap Up Button |
| **Right (右)** | `Right Arrow (→)` | Tap Right Button |

### Judgments (判定)

*   **PERFECT:** 1000 pts
*   **GREAT:** 700 pts
*   **GOOD:** 400 pts
*   **MISS:** Combo break

## 🚀 Getting Started (始め方)

Since this project uses modern web features (AudioContext, Local File Access), it is recommended to run it via a local web server rather than opening `index.html` directly, although basic features may work directly.

モダンなWeb機能（AudioContextなど）を使用しているため、ローカルWebサーバー経由での実行を推奨します。

### Quick Start with Python

If you have Python installed:
Pythonがインストールされている場合:

```bash
# Run server in the project directory
python3 -m http.server
# or
python -m http.server

# Open in browser
# http://localhost:8000
```

### Quick Start with Node.js

If you have Node.js installed:
Node.jsがインストールされている場合:

```bash
npx serve .
```

## 🛠️ Technologies (使用技術)

*   **HTML5 / CSS3** (Grid, Flexbox, CSS Variables)
*   **JavaScript (ES6+)**
*   **HTML5 Canvas API** (Rendering game visuals)
*   **Web Audio API** (Audio processing)
*   **YouTube IFrame Player API** (Video streaming)

## 📄 License

This project is open source. Feel free to modify and distribute.
本プロジェクトはオープンソースです。自由に改変・配布してください。
