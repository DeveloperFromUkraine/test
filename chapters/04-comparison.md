# 04 — Federation vs Single-SPA: When to Use What?

| Feature               | Module Federation      | Single-SPA             |
|-----------------------|------------------------|------------------------|
| Tech Agnostic         | ❌ Mostly JS/Webpack    | ✅ Fully agnostic       |
| Boilerplate           | ✅ Low                  | ❌ High                 |
| Runtime Flexibility   | ✅ Dynamic loading      | ✅ Full control         |
| Complexity to Start   | ✅ Easier               | ❌ More setup needed    |
| Best for              | Team-led component sharing | Legacy integration / full app control |

### 🔎 Summary

Use **Module Federation** when:
- You’re working with teams already using Webpack
- You want fast integration with low overhead

Use **Single-SPA** when:
- You need true framework independence
- You’re combining legacy SPAs with new ones
