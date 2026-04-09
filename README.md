# Nusu Bestie Chatbot 💖✨

Nusu is a premium, super cute AI best friend and closest companion, powered by Gemini 3.0. This application features a modern dark theme with glassmorphism, 3D neural core visuals, and cinematic animations.

## Features

- **Nusu Personality:** A supportive, caring, and playful AI bestie.
- **3D Neural Core:** Dynamic, morphing 3D orb background using Three.js and React Three Fiber.
- **Cinematic UI:** Premium glassmorphism effects, blur-to-focus message entrances, and high-end animations.
- **Voice Input:** Integrated Web Speech API for hands-free chatting.
- **Responsive Design:** Fully optimized for all screen sizes.
- **Advanced Intelligence:** Powered by Google's Gemini API.

## Tech Stack

- **Frontend:** React 19, Vite, TypeScript
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion (Motion)
- **3D Graphics:** Three.js, React Three Fiber, Drei
- **AI:** @google/genai (Gemini API)
- **Icons:** Lucide React

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- A Gemini API Key (from [Google AI Studio](https://aistudio.google.com/))

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd nusu-bestie
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Gemini API key:
   ```env
   VITE_GEMINI_API_KEY=your_actual_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## Deployment to GitHub Pages

1. Install the `gh-pages` package:
   ```bash
   npm install gh-pages --save-dev
   ```

2. Add the following scripts to your `package.json`:
   ```json
   "predeploy": "npm run build",
   "deploy": "gh-pages -d dist"
   ```

3. Add a `base` property to your `vite.config.ts`:
   ```typescript
   export default defineConfig({
     base: '/<your-repo-name>/',
     // ... rest of config
   })
   ```

4. Run the deployment command:
   ```bash
   npm run deploy
   ```

## License

MIT
