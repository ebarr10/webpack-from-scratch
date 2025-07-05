# What is Webpack?

**Webpack** is a **module bundler**. Its main job is to:

- Take your JavaScript (and other assets like CSS, images) **and bundle them into one or more files** that browsers can efficiently load.
- Manage dependencies between modules — so if file A imports B and C, Webpack figures out the order and creates a bundle.
- Optimize the output by minifying, tree-shaking unused code, splitting code (code-splitting), and more.
- Allow use of **loaders** to transform files — e.g., convert SCSS to CSS, inline images, or handle fonts.

### Why do you need it?

Browsers don’t natively understand modern modular JavaScript (like `import/export`) or non-JS assets. Webpack **packages** all your resources into browser-ready bundles.

---

# What is Babel?

**Babel** is a **JavaScript compiler/transpiler**. Its main purpose is to:

- Convert **modern JavaScript (ES6/ESNext+)** into backwards-compatible JavaScript that runs in older browsers.
- Transform syntax that browsers might not support yet (like arrow functions, async/await, classes).
- Enable use of next-gen JS features without worrying about browser support.
- Optionally compile JSX (React’s syntax) into regular JS.

### Why do you need it?

Not all browsers support the latest JS features. Babel **ensures your code runs everywhere** by transpiling it to widely supported versions.
