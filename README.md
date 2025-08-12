# ABT Workflow — Powered by B-HD™ & Sliz™

![NeXT Logo](https://github.com/B-HDtm/ABT/blob/main/ico.png)

Welcome to **ABT** — the ultimate multi-language syntax checking GitHub Actions workflow, crafted with love and brains by **B-HD™ & Sliz™**. This bad boy automatically checks your code syntax across **110+ programming languages** every time you push or open a pull request.

---

## Why ABT?

- 🚀 **Speedy & smart** — catches syntax errors before they wreck your build.
- 💼 **Multi-language support** — from Python and JavaScript to obscure languages like Nim and Futhark.
- 🤖 **Automated environment setup** — no manual installs, just plug and play.
- 🔥 **Scalable** — perfect for solo devs, startups, or massive teams.
- 🎉 **Made by the legends B-HD™ & Sliz™** — because quality matters.

---

## How It Works

- Runs on **Ubuntu latest** virtual environment.
- Detects your project files by extension.
- Runs syntax checks using official language tools or compilers.
- Skips jobs gracefully if no relevant files are found.
- Reports errors early, keeping your codebase clean and shiny.

---

## Supported Languages

A whopping **100+ languages** including but not limited to:

- Python, JavaScript, TypeScript, Go, Ruby, PHP, Java, C, C++, Kotlin
- Rust, Swift, Scala, Perl, Bash, Lua, Elixir, Haskell, R
- And many more — check the full list in `ABT.yml`

---

## Usage

Add `ABT.yml` to your `.github/workflows` folder in your repo:

```bash
git clone https://github.com/B-HDtm/ABT
cd ABT
mkdir -p .github/workflows
cp ABT.yml .github/workflows/
git add .github/workflows/ABT.yml
git commit -m "Add ABT multi-language syntax checker"
git push
```

**OR**

- Just copy file (ABT.yml)
- Create in Desktop .github/workflows folder
- Added ABT.yml to .github/workflows
- Upload the .github/workflows/ABT.yml for you repository


From now on, every push or PR triggers syntax checks automatically.

---

## Support & Feedback

Got ideas? Bugs? Want more languages? Hit us up!

- **Email:** markd.voznyuk@gmail.com
- **Issues:** [issues](https://github.com/B-HDtm/ABT/issues)
- **Community:** [B-HD™ Public Chat](https://github.com/orgs/B-HDtm/discussions/2)

---

## License

MIT License — because freedom to code is everything.

---

**Built with pride by B-HD™ & Sliz™** — making dev life cleaner, faster, and cooler. 💥
