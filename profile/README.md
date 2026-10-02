## Know what your code can touch, before it ships

**PermLang** is a build-time permission check for TypeScript. It keeps an
inventory of what your code can reach (servers, files, secrets, databases,
system commands) and flags any pull request that reaches something new, before
it's merged.

Built for the age of AI-written code, where one added line can send customer
data somewhere new, and the tests still pass.

```bash
npm install --save-dev permlang
npx permlang init src --workflow
```

| | |
| --- | --- |
| 📦 [**PermLang**](https://github.com/PermLang/PermLang) | The checker, the GitHub Action, and the docs |
| 🔍 [**Live demo**](https://github.com/PermLang/permlang-demo/pull/1) | A pull request where the tests pass and PermLang catches data going to a broker |
| 📘 [**Getting started**](https://github.com/PermLang/PermLang/blob/main/docs/getting-started.md) | From zero to a pull-request check in ten minutes |

Open source under Apache 2.0. Found a way past it? Please
[report it privately](https://github.com/PermLang/PermLang/security).
