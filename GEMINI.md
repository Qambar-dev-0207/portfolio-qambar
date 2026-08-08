# PathOS: AI Engineer Portfolio Showcase

## Project Overview
PathOS is a high-tech, high-performance professional portfolio designed for an AI & XR Systems Engineer. It features a cyberpunk "Neural Matrix" aesthetic, integrated AI interaction, and immersive 3D elements.

### Core Technologies
- **Frontend:** React (TypeScript), Vite, TailwindCSS
- **Animations:** Framer Motion
- **3D Elements:** Spline, Three.js (@react-three/fiber)
- **AI Intelligence:** Groq API (Llama 3.1 8B Instant)
- **Icons:** Lucide-React
- **Hosting:** Netlify

### Key Features
- **Neural Chatbot:** Real-time AI interaction powered by Groq and Llama 3.1, pre-conditioned with resume data.
- **System Terminal:** A hidden CLI (Ctrl + Alt) for technical exploration and AI queries.
- **Interactive Stack:** Canvas-based skill constellations and live GitHub contribution heatmap.
- **Project Modules:** Glassmorphism project cards with 3D hover effects and detailed popup insights.
- **Responsive Fluidity:** Custom `clamp()` typography and optimized mobile layouts.

---

## Building and Running

### Prerequisites
- Node.js (v18+)
- npm or bun

### Commands
- **Install Dependencies:** `npm install`
- **Development Mode:** `npm run dev`
- **Production Build:** `npm run build`
- **Preview Build:** `npm run preview`

---

## Development Conventions

### Component Architecture
- Components are located in `src/components/`.
- UI primitives (shadcn-like) are in `src/components/ui/`.
- Pages are defined in `src/pages/`.

### Styling & Aesthetics
- **Theme:** "PathOS" Branding (Emerald Green accents, high-contrast dark mode).
- **Typography:** JetBrains Mono for technical elements, Space Grotesk/Jakarta for headings.
- **Visuals:** Heavy use of `backdrop-blur`, `mix-blend-mode`, and custom SVG noise overlays.
- **Borders:** Subtle `white/5` or `emerald-500/20` borders for a futuristic HUD feel.

### SEO & Bot Accessibility
- Core professional data is mirrored in `index.html` via `<noscript>` and JSON-LD for LLM crawlers.
- `robots.txt` explicitly allows GPTBot and ChatGPT-User.

---

## Environment Configuration
The project uses a `.env` file for the following:
- `VITE_GROQ_API_KEY`: Required for chatbot and terminal AI functionality.
