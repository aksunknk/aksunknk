<div align="center">

# aksunknk

**多言語・フルスタック・クロスプラットフォームを跨いで「動くもの」を設計・実装するエンジニア**

TypeScript / Python を軸に、Web・デスクトップ・モバイル・ベクトル検索基盤まで一気通貫で構築します。

</div>

---

## 技術スタック

**言語**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**フロントエンド / モバイル / デスクトップ**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

**バックエンド / インフラ**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

## 代表プロジェクト

### [Lemma](https://github.com/aksunknk/Lemma) — 384次元ハイブリッドベクトル書籍検索エンジン
120万件の書籍を `SentenceTransformers (e5-small)` で384次元ベクトル化し、`sqlite-vec` による KNN 距離計算と四象限メタデータフィルタを併用。Pandas インメモリ展開を排した完全ステートレス設計で、120万件・1000連続クエリのストレステストでメモリリーク0%を達成。
`Python` `FastAPI` `sqlite-vec` `React` `Docker` `uv`

### [axiom](https://github.com/aksunknk/axiom) — クロスプラットフォーム自己状態トラッカー
5つの生体指標から非線形に **SYSTEM INTEGRITY** を算出する計器板UI。同一コードベースから Web / デスクトップ（Tauri）/ Android（Capacitor）を生成。任意でローカルLLM（LM Studio）連携によるノート構造化に対応。
`TypeScript` `React` `Rust/Tauri` `Capacitor` `FastAPI`

### [Project-Withham](https://github.com/aksunknk/Project-Withham) — ハムスター健康記録アプリ（Android / Expo）
飼育記録・分析（体重推移グラフ、へやんぽ集計）を端末ローカルSQLiteで行うオフラインアプリ。Expo SDK 54 / React Native、EAS Build による APK 配布。
`React Native` `Expo` `expo-sqlite`

---

## 設計思想

- **ステートレス & リソース効率** — メモリ死重を排し、I/O効率を優先したアーキテクチャ
- **一気通貫** — フロント・バック・インフラ・配布までを単独で設計・実装
- **クロスプラットフォーム** — 単一コードベースから複数ターゲットを生成

---

## GitHub Stats

<div align="center">

![aksunknk's GitHub stats](https://github-readme-stats.vercel.app/api?username=aksunknk&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=aksunknk&layout=compact&theme=tokyonight&hide_border=true)

</div>

---


- 志望職種・分野（例: バックエンド / フルスタック）実務での開発は未経験のためとにかく実務でコードを書きたいしチームで業務を行うという経験を積みたいです。
- 連絡先（メール / ポートフォリオURL / X 等）aksaks.suak@gmail.com

