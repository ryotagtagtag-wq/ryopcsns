# ryopcsns - AI-Powered Safety SNS Hub
### Developer: game_ryo

---

## 日本語 プロジェクト概要
ryopcsnsは、掲示板、リアルタイムチャット、画像ブログを統合したSNS集合体です。Cloudflareのエコシステムを活用し、AIと保護者が連携してユーザーを保護する次世代型の安全なSNSを目指しています。

### 主な機能
- SNSポータル: 掲示板・チャット・ブログの各機能への統合エントリーポイント。
- AI検閲 (Hugging Face): 全投稿をリアルタイムでスキャンし、不適切なコンテンツを自動的に制限。
- AI対話 (Groq/Llama 3): 高速推論による応答。同時に背後で深刻度判定フラグ（0-2）を算出し記録。
- 保護者管理システム: 
  - アカウント紐付け: 親のメール承認プロセスを経ることでアカウントを有効化。
  - 緊急停止機能: 保護者からのメールをAIが解析し、停止要請を検知した場合は即座にアカウントをロック。
  - 安全度レポート: 過去の活動データからAIが安定度スコアを算出し、保護者用画面へ提示。

---

## English Project Overview
ryopcsns is an all-in-one SNS hub integrating forums, real-time chat, and image blogs. Leveraging the Cloudflare ecosystem, it aims to be a next-generation safe SNS where AI and parents collaborate to protect users.

### Key Features
- SNS Portal: Centralized entry point for Forum, Chat, and Blog modules.
- AI Content Moderation (Hugging Face): Real-time scanning and automatic restriction of inappropriate content.
- AI Interaction (Groq/Llama 3): High-speed inference for user support with background gravity scoring (0-2).
- Parental Control System:
  - Account Linkage: Registration requires parental approval via email verification.
  - Emergency Stop Trigger: AI parses parental emails to detect lock requests and freezes accounts instantly.
  - Safety Score: AI-driven analysis of activity to provide a stability report on the parent dashboard.

---

## Technology Stack
- Frontend: Cloudflare Pages / HTML / CSS (Glassmorphism UI) / JavaScript
- Backend: Cloudflare Workers
- Database: Cloudflare D1 (Database name: snsdb)
- Media Storage: Cloudinary
- AI Engine: Groq API / Hugging Face Inference API
- Security/Mail: Cloudflare Email Routing

---

## License
This project is licensed under the MIT License.
Copyright (c) 2024 game_ryo
