# AI Books Hub (Next.js + Tailwind + Framer Motion)

A ready-to-run demo website featuring:
- Home, About, Contact, AI Demo pages
- AI chatbot via OpenAI API (`/api/chat`)
- Searchable AI books (client-side)
- Dark/Light mode toggle
- Smooth page transitions

## Quick Start
1. Install dependencies
```bash
npm install
```
2. Add your OpenAI key
Create `.env.local` in project root:
```
OPENAI_API_KEY=sk-...NQAA
3. Run dev server
```bash
npm run dev
```
Open http://localhost:3000

## Notes
- This project uses the Pages Router for simplicity.
- Images are local SVG placeholders and can be replaced.
- Chatbot is scoped to AI/AI-books questions by a system prompt.
