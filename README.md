# Jupiter-Hackthon

**Jupiter Terminal vs API**  
[Jupiter Terminal](https://terminal.jup.ag/) is a plug-and-play UI that can be embedded directly in your app via HTML.  
The Jupiter **API** uses quote and swap endpoints and requires building a custom front-end UI.

---

## 🚀 Usage

This repo is a **reference implementation**. It’s not production-ready, but a great base for learning and experimenting.

### 🛠 Prerequisites
- Get an API key from [Helius](https://www.helius.dev/)
- Add your key in the HTML or `create-solana-dapp` implementation

---

## 📁 Project Structure

### HTML Terminal
- Uses a plain HTML file with a script to load Jupiter Terminal via CDN.

### Create-Solana-Dapp
- Based on the [create-solana-dapp](https://github.com/solana-developers/create-solana-dapp) template.
- Uses a modern React/Vite setup.
- Swap feature lives at `/swap` route.

---

## 🧪 Setup Instructions

```bash
git clone https://github.com/AlmostEfficient/jupiter-swap/
cd create-solana-dapp/web
npm install
npm run dev
