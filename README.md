# Neon Hero - Prism Edition (ネオン・ヒーロー：プリズム・エディション)

**Neon Hero** is a browser-based rhythm action game with a vibrant cyberpunk aesthetic. Play with your favorite music from YouTube!
This **Prism Edition** introduces new themes, global rankings, and enhanced community features.

**ネオン・ヒーロー**は、鮮やかなサイバーパンク・スタイルのブラウザベースのリズムアクションゲームです。YouTubeの動画を使って、お気に入りの曲で遊ぶことができます！
**プリズム・エディション**では、新テーマ、グローバルランキング、コミュニティ機能が追加されました。

![Neon Hero Screenshot](https://via.placeholder.com/800x450?text=Neon+Hero+Prism+Edition) 
*(Screenshots coming soon / スクリーンショットは準備中です)*

## 🎮 Repository Info

*   **Repository Name:** `neon-hero`
*   **Description:** A browser-based cyberpunk rhythm game that generates charts from YouTube videos. Features global rankings and theme customization. (YouTubeの動画から譜面を生成して遊べる、ブラウザベースのサイバーパンク風リズムゲーム。ランキングやテーマ変更機能を搭載。)

## 🚀 Live Demo (ライブデモ)

You can play Neon Hero live on GitHub Pages:
[https://dma-cmyk.github.io/neon-hero/](https://dma-cmyk.github.io/neon-hero/)

## ✨ Features (特徴)

*   **Dynamic Chart Generation (動的譜面生成):** Automatically generates note patterns based on the video duration and selected difficulty.
*   **Dual Themes (デュアルテーマ):**
    *   **Deep Space Neon (Dark):** The classic cyberpunk look.
    *   **Opal Prism (Light):** A bright, clean aesthetic for a fresh experience.
*   **Global Ranking (グローバルランキング):** Compete with players worldwide! Supports player names, secure tripcodes, and comments.
*   **Shared Library (共有ライブラリ):** Discover popular tracks played by the community (Daily, Weekly, Monthly rankings).
*   **Multiple Inputs (多様な操作):**
    *   **Keyboard:** Fully customizable key bindings.
    *   **Touch:** Optimized for mobile play.
    *   **Gamepad:** Connect your controller for an arcade-like experience.
*   **Quality of Life:**
    *   **Intro Skip:** Jump straight to the music for videos with long intros.
    *   **Share URL:** Share your favorite charts with a simple link.

## 🕹️ How to Play (遊び方)

The goal is to hit the falling notes at the right timing as they reach the judgment line.
落ちてくるノーツが判定ラインに重なるタイミングで操作します。

### Controls (操作方法)

Default controls (customizable in settings):
デフォルトの操作（設定で変更可能）:

| Lane | PC (Keyboard) | Mobile (Touch) | Gamepad |
| :--- | :--- | :--- | :--- |
| **Left (左)** | `Left Arrow (←)` | Tap Left Button | `Button 14` / `Button 0` |
| **Down (下)** | `Down Arrow (↓)` | Tap Down Button | `Button 13` / `Button 1` |
| **Up (上)** | `Up Arrow (↑)` | Tap Up Button | `Button 12` / `Button 3` |
| **Right (右)** | `Right Arrow (→)` | Tap Right Button | `Button 15` / `Button 2` |

### Judgments (判定)

*   **PERFECT:** 1000 pts
*   **GREAT:** 700 pts
*   **GOOD:** 400 pts
*   **MISS:** Combo break

## 🚀 Getting Started (始め方)

Since this project uses modern web features (AudioContext, Firebase), it is recommended to run it via a local web server.

モダンなWeb機能（AudioContext, Firebaseなど）を使用しているため、ローカルWebサーバー経由での実行を推奨します。

### Quick Start with Python

```bash
# Run server in the project directory
python3 -m http.server
# or
python -m http.server

# Open in browser
# http://localhost:8000
```

### Quick Start with Node.js

```bash
npx serve .
```

## 🛠️ Technologies (使用技術)

*   **Front-end:** HTML5, CSS3 (Variables, Grid, Flexbox), JavaScript (ES6+)
*   **Graphics:** HTML5 Canvas API
*   **Audio/Video:** Web Audio API, YouTube IFrame Player API
*   **Backend (BaaS):** Firebase (Authentication, Firestore) for rankings and library features.

## 📄 License

This project is open source. Feel free to modify and distribute.
本プロジェクトはオープンソースです。自由に改変・配布してください。