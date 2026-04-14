# ryopcsns - High-Performance AI-Integrated SNS Hub
### Developer: game_ryo

---

## 日本語 プロジェクト概要
ryopcsnsは、掲示板、リアルタイムチャット、ブログ機能を統合した次世代型SNSプラットフォームです。子供から大人まで全世代が安全に使用できるよう、CloudflareのインフラとAI技術を組み合わせた高度なセキュリティと利便性を両立しています。

### 主な機能
- 統合ポータル: 掲示板・チャット・ブログの各機能へシームレスにアクセス。
- AIコンテンツ保護 (Hugging Face): 全投稿をAIがリアルタイム監視。誹謗中傷や荒らし行為を自動で抑制。
- 爆速AIチャット (Groq/Llama 3): 高速レスポンスによる高度な対話体験を提供。
- セキュリティ・リンクシステム: 
  - 二段階承認プロセス: 登録時のメール認証による確実な本人確認。
  - 緊急リモートロック: 端末紛失やアカウント乗っ取り時、登録メールからAI経由の指示で即座にアカウントを保護。
  - 活動ログ分析: AIが利用状況を分析し、ユーザーの安全なデジタルライフをサポート。

---

## English Project Overview
ryopcsns is a high-performance SNS hub integrating forums, real-time chat, and blogs. Designed for users of all ages, it combines Cloudflare’s infrastructure with cutting-edge AI to deliver a secure and seamless social experience.

### Key Features
- Centralized Portal: Seamless access to forums, chat rooms, and blog modules.
- AI Content Protection (Hugging Face): Real-time AI monitoring to mitigate harassment and ensure a healthy community environment.
- Ultra-Fast AI Interaction (Groq/Llama 3): Powered by Groq for instantaneous and sophisticated conversational experiences.
- Advanced Security Linkage:
  - Two-Step Verification: Reliable identity confirmation via email during the registration process.
  - Emergency Remote Lock: Instantly freeze accounts via AI-parsed email commands in case of device theft or account compromise.
  - Activity Analysis: AI-driven insights to maintain user safety and digital well-being.

---

## Technology Stack
- Frontend: Cloudflare Pages / HTML / CSS (Modern Glassmorphism UI) / JavaScript
- Backend: Cloudflare Workers
- Database: Cloudflare D1 (Database name: snsdb)
- Media Storage: Cloudinary
- AI Engine: Groq API / Hugging Face Inference API
- Security/Mail: Cloudflare Email Routing

---

## License
This project is licensed under the MIT License.
Copyright (c) 2024 game_ryo
