
# Awsomely 🚀

**Awsomely** is an AI‑powered, low‑code web code editor and development agent — built in Bangladesh — designed to **build, ship, preview, and refine** code directly in the browser.  
It combines **WebAssembly performance**, **Vercel AI SDK intelligence**, and a **mobile‑friendly UI** to deliver a next‑generation developer experience.

---

## ✨ Features

- **AI‑Driven Development Loop**  
  Edit → Build → Preview → Refine — all guided by an AI agent.
- **WebAssembly Sandbox**  
  Near‑native performance for compiling, bundling, and running code securely in‑browser.
- **React CodeMirror 6 Editor**  
  Lightweight, extensible, and mobile‑friendly with syntax highlighting and linting.
- **Shadcn UI Components**  
  Accessible, themeable, and consistent UI across devices.
- **Vercel AI SDK Integration**  
  Streaming responses, tool calling, and multimodal capabilities.
- **Gist‑like Sharing**  
  Save and share code snapshots via Vercel KV/Blob (Supabase/GitHub Gist planned).
- **Mobile‑First Design**  
  Optimized layouts and touch‑friendly controls.

---

## 🛠 Tech Stack

| Layer            | Choice |
|------------------|--------|
| **Frontend**     | [Vite](https://vitejs.dev/) + React + TypeScript |
| **Editor**       | [React CodeMirror 6](https://codemirror.net/) |
| **UI**           | [Shadcn UI](https://ui.shadcn.com/) |
| **AI Layer**     | [Vercel AI SDK](https://sdk.vercel.ai/) + Gemini via [OpenRouter](https://openrouter.ai/) |
| **WASM Tooling** | `esbuild-wasm` (bundling) → `swc-wasm` (transforms) |
| **Storage**      | Vercel KV/Blob (Supabase & GitHub Gist planned) |

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/likhonsheikhofficial/Awsomely.git
cd Awsomely

# Install dependencies
npm install

# Start development server
npm run dev


---

⚙️ Configuration

Create a `.env` file in the project root:

VITE_OPENROUTER_API_KEY=your_openrouter_key
VITE_VERCEL_AI_KEY=your_vercel_ai_key


---

🚀 Usage

1. Open the editor in your browser.
2. Write or paste code in the React CodeMirror editor.
3. Click “Build & Preview” — code is compiled in a WebAssembly sandbox.
4. Refine with AI — ask Awsomely to improve, debug, or extend your code.
5. Share — save your project as a gist-like snapshot.


---

📚 Roadmap

• Monaco “Pro Mode” for advanced desktop editing
• Supabase backend for private projects & version history
• GitHub Gist integration
• Offline/local AI model support (WebLLM/MLC)
• Multi‑language support (Python, Rust, etc. via WASM)


---

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

---

📄 License

MIT License © 2025 Likhon Sheikh


---

