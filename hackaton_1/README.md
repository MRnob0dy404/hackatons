# PyLearn — Learn Python by Doing

**PyLearn** is an interactive web app that teaches Python one concept at a time. For each topic you get a short, plain-language explanation, then a **fill-in-the-code exercise**. When you submit, your code is checked automatically: if it's correct, you move on; if it's wrong, the app reveals the correct answer **and explains why it works** — so every mistake becomes a lesson.

---

## What it does

- **Explain → Practice → Check** loop for each lesson:
  1. A bite-sized explanation of a Python concept (e.g. variables, loops, functions).
  2. A partially written code snippet with a gap for you to fill in.
  3. Instant feedback: ✅ correct, or ❌ with the **right answer and a clear reason** why it's right.
- **Learn from mistakes** — wrong answers always come with an explanation, not just a red cross.
- **Progressive path** — lessons build from basics (print, variables) toward loops, conditionals, and functions.
- **Runs entirely in the browser** — no installation, no login, no setup for the learner.

## Who it is for

- **Absolute beginners** taking their first steps in programming.
- **Students and self-learners** who want structured, guided practice instead of a blank editor.
- **People without access to formal coding courses** who need a free, low-barrier way to start.

No prior programming experience is required — only a device with a web browser.

## Which SDG it addresses and why

**SDG 4 — Quality Education.**

PyLearn supports **inclusive, equitable, and free access to a valuable modern skill: coding.** Learning Python normally requires paid courses, a set-up development environment, or a teacher to check your work and explain your errors. PyLearn removes those barriers: it delivers the *explanation, the practice, and the personalized feedback* that a tutor would give — for free, in any browser. By making the "why" behind each answer visible, it builds real understanding rather than rote copying, which is the essence of quality education.

## How to run it

**Use it online (recommended):**
Open the deployed link in any modern browser — that's it. No sign-up or installation needed.

> Live app: `<paste your Bolt.new / deployment URL here>`

**Run it locally (from the source code):**

1. Make sure you have **Node.js** installed (v18 or newer).
2. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd pylearn
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the app:
   ```bash
   npm run dev
   ```
5. Open the URL shown in the terminal (usually `http://localhost:5173`) in your browser.

---

*Built with Bolt.new for the AI for Good Hackathon — Week 1 (SDG 4: Quality Education).*
