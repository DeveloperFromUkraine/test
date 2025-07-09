# 03 — Single-SPA Approach

Single-SPA is a JavaScript framework for orchestrating multiple frontend apps in one page.

### 🔧 How it works

- Each app is a separate SPA (React, Angular, Vue, etc.)
- A root-config app loads them using lifecycle hooks (`mount`, `unmount`, `bootstrap`)
- Apps are registered and controlled via routing

### ✅ Pros

- Framework-agnostic (can combine React, Angular, etc.)
- Decoupled deployments
- Battle-tested

### ❌ Cons

- More boilerplate
- Manual orchestration overhead
- More effort to coordinate shared state/styling
