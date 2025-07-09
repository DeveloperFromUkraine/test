# 02 — Module Federation (Webpack 5)

Module Federation is a native Webpack 5 feature that allows separate builds to dynamically share code at runtime.

### 🔧 How it works

- Each app (remote) exposes parts of its code
- A host app consumes them via `remoteEntry.js`
- No need for runtime orchestration frameworks

### ✅ Pros

- Native Webpack integration
- Lazy loading of remotes
- Less boilerplate than Single-SPA
- Great for team autonomy

### ❌ Cons

- Tight coupling to Webpack
- Can get complex with shared dependencies and version mismatches
