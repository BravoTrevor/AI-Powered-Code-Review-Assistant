# AI Code Review Assistant 🤖✨

[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue?logo=typescript)](https://www.typescriptlang.org)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT4o-purple)](https://openai.com)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

An intelligent GitHub pull request reviewer that provides:
- **Automated code quality analysis**
- **Security vulnerability detection**
- **Performance optimization suggestions**
- **Interactive diff visualization**

![Demo GIF](https://user-images.githubusercontent.com/.../demo.gif)

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- GitHub account
- OpenAI API key

### Installation
git clone https://github.com/your-username/ai-code-reviewer.git
cd ai-code-reviewer
pnpm install
echo "OPENAI_API_KEY=your_key" > .env.local
echo "GITHUB_CLIENT_ID=your_id" >> .env.local
echo "GITHUB_CLIENT_SECRET=your_secret" >> .env.local

### 🧩 How It Works
Code Submission → GitHub webhook triggers review
Context Analysis → LangChain chunks code/docs
LLM Processing → GPT-4o evaluates against rules
Feedback Delivery → Annotated comments on PR
