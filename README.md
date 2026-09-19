# Vasily Argounov

Playground to practice and experiment with AI-assisted programming.

**[Explore the portfolio →](https://vasyapym.github.io)** · [Source & engineering notes](https://github.com/vasyapym/vasyapym.github.io) · [Email](mailto:vasyapym@gmail.com)

## One react site.

Each project in **[vasyapym.github.io](https://vasyapym.github.io/)** is a self-contained module with its own tests.

### [Raft Cluster →](https://vasyapym.github.io/projects/raft-cluster/)

Crash the leader or cut a link.

**Underneath:** a Rust core compiled to WebAssembly, with a Canvas 2D view.

### [Cat Runner →](https://vasyapym.github.io/projects/kitty-run/)

A pastel endless runner with bullet-time dash, ghost replay, and a procedural soundtrack.

**Underneath:** deterministic simulation, React Three Fiber, and WebAudio.

### [Evening Forest →](https://vasyapym.github.io/projects/evening-forest/)

An 8-bit first-person walk through a forest at dusk.

**Underneath:** procedural terrain, React Three Fiber, custom shaders, and a custom postprocessing pass.

### [Explosion →](https://vasyapym.github.io/projects/explosion/)

A paper-lantern moon detonates into 600 shards.

**Underneath:** physics running in fragment shaders on the GPU, backed by a Rust/WebAssembly core.

### [Planck to Now →](https://vasyapym.github.io/projects/planck-to-now/)

Scrub cosmic history from the Planck epoch to the present on a logarithmic time scale.

**Underneath:** Three.js.

### [Practice Map →](https://vasyapym.github.io/projects/practice-map/)

A working map for technical practice, connecting concept routes with exercises.

**Go deeper:** approximately 5,000-word lessons and review-note export.

## How it fits together

- **Module contract:** Vite/React discovers projects through a typed `ProjectModule` contract via `import.meta.glob`. Adding a project means adding a directory.
- **Custom landing hero:** a Canvas 2D “glyph field,” without WebGL or animation libraries.

The foundation is **React 19, TypeScript, and Vite 7**, with **two Rust → WebAssembly crates**. npm workspaces organize the code; GitHub Actions and GitHub Pages handle delivery.

[Read the portfolio README for the architecture and development details →](https://github.com/vasyapym/vasyapym.github.io)

---

**Get in touch:** [vasyapym@gmail.com](mailto:vasyapym@gmail.com)
