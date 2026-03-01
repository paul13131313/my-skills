# SKILLS.md - 技術スキルマップ
> 新しいチャット開始時にこのファイルを読み込ませること。
> 新しい技術を習得したら随時更新する。

## 🟢 実務レベル（プロジェクトで使用済み）

### フロントエンド
- **HTML / CSS / JavaScript** — 全プロジェクトの基盤
- **React** — MY RANKING、生成新聞など複数プロジェクト
- **Next.js** — フルスタックアプリ構築
- **Tailwind CSS** — UIスタイリング
- **Web Audio API** — 音楽アプリ、リズムゲーム、アンビエントサウンド
- **PWA** — 生成新聞のオフライン対応・インストール
- **Three.js** — 3Dグラフィックス（SOUND COSMOS）
- **WebGL2 / GLSL シェーダー** — 流体シミュレーション（FLUID NOISE）
- **TensorFlow.js** — ブラウザ上ML推論・手認識（AIR SYNTH）
- **WebRTC (PeerJS)** — P2Pリアルタイム通信（SYNC PAD）
- **D3.js** — データビジュアライゼーション・Force Simulation（SKILL GALAXY）
- **Chrome Extension (Manifest V3)** — ブラウザ拡張開発（COLOR THIEF）
- **Web Workers** — CPU並列処理（FRACTAL DIVE）
- **Web Speech API** — ブラウザ音声認識（VOICE MEMO）
- **IndexedDB** — ブラウザ内永続ストレージ（VOICE MEMO）
- **CSS Scroll-Driven Animations** — スクロール連動アニメーション（SCROLL STAGE）
- **Intersection Observer** — 要素可視性検出・遅延表示（SCROLL STAGE）
- **Canvas 2D ゲーム開発** — ゲームループ・当たり判定・状態管理（PIXEL DODGE）
- **WebSocket** — リアルタイム双方向通信（LIVE BOARD）
- **HTML Drag and Drop API** — ネイティブドラッグ&ドロップ（KANBAN FLOW）
- **View Transitions API** — ページ内アニメーション遷移（KANBAN FLOW）
- **Web Animations API (WAAPI)** — プログラマティックアニメーション制御（MOTION LAB）
- **Web Components (Custom Elements v1 / Shadow DOM)** — 再利用可能UIコンポーネント設計（COMPONENT KIT）
- **MediaPipe Face Landmarker** — 顔468点ランドマーク検出・表情認識（FACE MIRROR）
- **MediaPipe Image Segmenter** — リアルタイム人物セグメンテーション（LIQUID WALL）
- **File System Access API** — ローカルファイル/フォルダの直接読み書き（FOLDER VISION）
- **MediaPipe Pose Landmarker** — 全身33点ポーズ推定・骨格検出（BODY PARTICLES）
- **MediaPipe Object Detector** — 物体検出・バウンディングボックス（DARK SCANNER）
- **WebGPU Compute Shader** — GPU並列計算パイプライン（PARTICLE STORM, BODY PARTICLES）
- **WebGPU Render Pipeline** — GPUインスタンス描画・加算ブレンド（PARTICLE STORM, BODY PARTICLES）
- **YouTube IFrame Player API** — YouTube動画のプログラム制御・埋め込み（PUNCH PUNCH PUNCH）
- **oEmbed API** — 動画メタデータ取得・縦型動画フィルタリング（PUNCH PUNCH PUNCH）
- **Vite + TypeScript** — 高速ビルドツール＋型安全な開発（Silent Call）
- **CSS writing-mode: vertical-rl** — 日本語縦書きレイアウト（Silent Call）
- **CSS Custom Properties（動的スタイリング）** — JavaScript連携のリアルタイムスタイル制御（Silent Call）
- **navigator.vibrate() API** — デバイス振動フィードバック（Silent Call）
- **Google Fonts (Noto Serif JP / Noto Sans JP)** — 日本語Webフォント活用（Silent Call）
- **html2canvas** — DOM→Canvas画像化・SNSシェア用画像保存（KANJI ME）
- **Web Share API** — ファイル付きネイティブ共有・画像+テキスト+URLのSNSシェア（KANJI ME）
- **PWA マニフェスト / apple-touch-icon** — ホーム画面アイコン対応（KANJI ME）
- **CSS position: absolute によるクレジット注釈オーバーレイ** — AI生成画像へのクレジット表記（台灣生成新聞）
- **object-fit: cover による画像トリミング** — 黒帯除去・アスペクト比調整（台灣生成新聞）
- **Canvas APIベースのピクセル分析** — 画像内の黒帯検出・自動トリミング判定（台灣生成新聞）
- **大規模HTML（base64画像埋め込み）の効率的編集** — 単一ファイル内の巨大base64画像管理（台灣生成新聞）
- **next/og (ImageResponse)** — Edge Runtimeで動的OGP画像生成・フォントサブセッティング（KANJI ME）
- **ISR (Incremental Static Regeneration)** — generateStaticParams＋revalidateで事前生成＋定期再検証（KANJI ME）
- **Vercel Analytics** — ページビュー・カスタムイベント計測（KANJI ME）

### バックエンド / インフラ
- **Cloudflare Workers** — 生成新聞のAPI・配信基盤、LIVE BOARDのWebSocketサーバー
- **Cloudflare Durable Objects** — ステートフルエッジコンピューティング（LIVE BOARD）
- **Upstash Redis** — サーバーレスKVストア（We TASK）
- **Supabase** — DB・認証（MY RANKINGなど）
- **Stripe** — 決済連携（生成新聞 月額サブスク）
- **OAuth認証** — ソーシャルログイン実装

### API連携
- **Claude API** — AI生成コンテンツ（生成新聞の記事生成）
- **RSS/Atomフィード解析** — Google News RSS、はてブhotentry、artscape・CINRA等の実データ注入（生成新聞）
- **Open-Meteo API** — 天気実データ取得・複数都市一括天気予報ティッカー（生成新聞）
- **Stooq CSV API** — 株価・為替データ取得（生成新聞）
- **LINE Messaging API** — Bot連携（体重記録システム）
- **YouTube Data API v3** — 動画検索・埋め込み可否チェック（PUNCH PUNCH PUNCH）
- **Chatwork API** — タスク完了通知・THANKSカード連携（We TASK）
- **Resend API** — トランザクションメール配信・独自ドメイン認証（生成新聞）

### ツール / デプロイ
- **GitHub Pages** — 静的サイトホスティング（カスタムドメイン対応）
- **Cloudflare Registrar** — ドメイン取得・DNS管理（seiseishinbun.com）
- **Vercel** — サーバーレス関数 + フロントエンドホスティング + KVストア（PUNCH PUNCH PUNCH, KANJI ME）
- **Claude Code (CC)** — AI支援開発のメインツール
- **Git / GitHub** — バージョン管理・リポジトリ運用

## 🟡 学習中 / 次に取り組む

- **MediaPipe 応用（物体検出の高度化）** — より複雑な検出シナリオ

## 📁 主要プロジェクト実績

| プロジェクト | 技術スタック | 概要 |
|---|---|---|
| 生成新聞 | React, Cloudflare Workers, Claude API, RSS/API実データ統合, Stooq CSV API, Open-Meteo API(天気ティッカー), Stripe, PWA, Resend | 月額300円 AI生成新聞サブスク（独自ドメイン seiseishinbun.com、朝刊:株価ティッカー/夕刊:天気予報ティッカー） |
| MY RANKING | React, Next.js, Supabase | フルスタック個人ランキングシステム |
| necoo | React | TikTok風猫動画ビューア |
| 台湾レストランガイド | HTML/CSS/JS | 台湾グルメ情報サイト |
| 音楽アプリ群 | Web Audio API | インタラクティブ楽器・リズムゲーム |
| 素材タッチ体験 | HTML/CSS/JS | インタラクティブ素材表現 |
| 体重記録Bot | LINE Messaging API | LINE連携の体重管理 |
| STUDIO PAUL | WebGL2/GLSL, CSS Scroll-Driven Animations, Intersection Observer | ポートフォリオ（WebGLノイズ背景 + スクロール演出） |
| SOUND COSMOS | Three.js, Web Audio API | 3Dオーディオビジュアライザー |
| FLUID NOISE | WebGL2, GLSL, Web Audio API | Audio Reactive 流体シミュレーション |
| AIR SYNTH | TensorFlow.js, Web Audio API | 手で空中演奏するAIシンセサイザー |
| SYNC PAD | WebRTC, PeerJS, Web Audio API | P2Pリアルタイム共演ドラムマシン |
| SKILL GALAXY | D3.js | インタラクティブ技術スキルマップ可視化 |
| COLOR THIEF | Chrome Extension, Manifest V3, Canvas API | ページ配色抽出Chrome拡張 |
| FRACTAL DIVE | Web Workers, Canvas API | 並列計算マンデルブロ集合エクスプローラー |
| VOICE MEMO | Web Speech API, IndexedDB, Web Audio API | リアルタイム音声文字起こしメモ |
| SCROLL STAGE | CSS Scroll-Driven Animations, Intersection Observer | スクロール演出ショーケース |
| PIXEL DODGE | Canvas 2D, Web Audio API | レトロ弾避けアーケードゲーム |
| LIVE BOARD | WebSocket, Cloudflare Durable Objects, Canvas 2D | リアルタイム共有ホワイトボード |
| KANBAN FLOW | Drag and Drop API, View Transitions API | ドラッグ&ドロップ カンバンボード |
| MOTION LAB | Web Animations API | アニメーションAPI実験室 |
| COMPONENT KIT | Web Components, Shadow DOM, Custom Elements | 再利用可能UIコンポーネントライブラリ |
| FACE MIRROR | MediaPipe Face Landmarker, Canvas 2D, Blendshapes | リアルタイム顔ランドマーク検出＆4エフェクト |
| LIQUID WALL | MediaPipe Image Segmenter, Canvas 2D, 流体シミュレーション | WEB会議用インタラクティブ流体背景 |
| FOLDER VISION | File System Access API, D3.js (treemap/sunburst/pack) | フォルダ構造インタラクティブ可視化ツール |
| PARTICLE STORM | WebGPU Compute Shader, Canvas | WebGPU 100万パーティクルシミュレーション |
| DARK SCANNER | MediaPipe Object Detector, Face Detector, Pose Landmarker, Canvas 2D | 軍事偵察分析風HUD画像ジェネレーター |
| BODY PARTICLES | MediaPipe Pose Landmarker, WebGPU Compute Shader, WebGPU Render Pipeline | カメラ姿勢検出×WebGPU 20万パーティクルインタラクション |
| SHEET MOVIE | Chrome Extension, Manifest V3, Canvas 2D, Web Audio API | Google Sheetsセル動画モザイクオーバーレイ拡張 |
| PUNCH PUNCH PUNCH | React, YouTube IFrame Player API, Vercel Serverless Functions | パンチくんTikTok風無限動画フィード |
| We TASK | Next.js, Upstash Redis, Chatwork API, Drag and Drop API | チーム雑務見える化ボード（THANKSカード・チュートリアル付き） |
| Silent Call | Vite, React, TypeScript, CSS writing-mode, navigator.vibrate() | 飲食店で声を出さずに店員を呼べるサイレントコールアプリ |
| KANJI ME | Next.js, TypeScript, Tailwind CSS, Claude API (Haiku), html2canvas, Web Share API, Vercel KV, Stripe, next/og, ISR, Vercel Analytics | 英語名をAI漢字変換。名前別URL＋動的OGP・SEO事前生成100名・Analyticsによるバイラルループ計測対応のフリーミアムアプリ |
| 台灣生成新聞 | HTML/CSS（単一ファイル）, AI画像生成, Canvas API, GitHub Pages | 台湾ニュースをAI翻訳・要約して毎日届ける新聞風メディア |

## 📝 運用ルール
1. 新しい技術を使ったら「実務レベル」に追加
2. 興味がある技術は「学習中」に追加
3. プロジェクト完了時にテーブルに追記
4. チャット開始時に「SKILLS.mdを読んで」と伝える
