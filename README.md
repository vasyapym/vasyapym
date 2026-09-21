# Vasily Argounov

Playground to practice and experiment with AI-assisted programming.

**[Explore the portfolio →](https://vasyapym.github.io)** · [Source & engineering notes](https://github.com/vasyapym/vasyapym.github.io) · [Email](mailto:vasyapym@gmail.com)

## One react site.

Each project in **[vasyapym.github.io](https://vasyapym.github.io/)** is a self-contained module with its own tests.

### [Waste of tokens →](https://vasyapym.github.io/projects/practice-map/)

An archive of AI outputs, a lesson space, and an open playground.

**Underneath:** sectioned lessons, persistent notes, and review-note export — all local, no account.

### [Spine →](https://vasyapym.github.io/projects/spine/)

Drag, nest and retune Flexbox and Grid layouts in the browser, then copy clean HTML+CSS.

**Underneath:** a Go core compiled to WebAssembly, with undo/redo.

### [Quicknotes →](https://vasyapym.github.io/projects/quicknotes/)

Local-first markdown notes with [[wiki-links]], live preview, and a command palette.

**Underneath:** static ES modules and Firebase sync — no build step.

### [Cat Runner →](https://vasyapym.github.io/projects/kitty-run/)

A pastel endless runner with bullet-time dash, ghost replay, and a procedural soundtrack.

**Underneath:** deterministic simulation, React Three Fiber, and WebAudio.

### [Raft Cluster →](https://vasyapym.github.io/projects/raft-cluster/)

Crash the leader or cut a link and watch a new term get elected.

**Underneath:** a Rust core compiled to WebAssembly, with a Canvas 2D view.

### [Evening Forest →](https://vasyapym.github.io/projects/evening-forest/)

An 8-bit first-person walk through a forest at dusk.

**Underneath:** procedural terrain, React Three Fiber, custom shaders, and a custom postprocessing pass.

### [Explosion →](https://vasyapym.github.io/projects/explosion/)

A paper-lantern moon detonates into 600 shards.

**Underneath:** physics running in fragment shaders on the GPU, backed by a Rust/WebAssembly core.

### [Planck to Now →](https://vasyapym.github.io/projects/planck-to-now/)

Scrub cosmic history from the Planck epoch to the present on a logarithmic time scale.

**Underneath:** Three.js.

## The realm

The landing page hides an opt-in full-screen layer — the deep: a dark abyss where each project is a bioluminescent creature you steer a warm lantern toward. WebGL fluid, Canvas 2D overlay, WebAudio synthesis; reduced-motion and no-WebGL fallbacks included.

## How it fits together

- **Module contract:** Vite/React discovers projects through a typed `ProjectModule` contract via `import.meta.glob`. Adding a project means adding a directory.
- **Custom landing hero:** a Canvas 2D “glyph field,” without WebGL or animation libraries.

The foundation is **React 19, TypeScript, and Vite 7**, with **Rust and Go cores compiled to WebAssembly**. npm workspaces organize the code; GitHub Actions and GitHub Pages handle delivery.

[Read the portfolio README for the architecture and development details →](https://github.com/vasyapym/vasyapym.github.io)

## Agentic workflow

All agentic orchestration, repository management, testing, and implementation is handled by GLM 5.3-Flash, which distributes scoped tasks and briefs to Claude Opus 4.8/5, Fable 5/5.1, and GPT Sol/6 Astra, then reconciles their outputs.

---

**Get in touch:** [vasyapym@gmail.com](mailto:vasyapym@gmail.com)
