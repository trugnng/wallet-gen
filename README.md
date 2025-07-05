# octra wallet generator

## quick Start

**download and start wallet generator web UI with a single command:**

**linux/macOS:**
```bash
curl -fsSL https://octra.org/wallet-generator.sh | bash
```

**windows:**
```powershell
powershell -c "irm octra.org/wallet-generator.ps1 | iex"
```

this command will:
- download the latest source code and build the wallet generator
- start the server and open the generator web UI page in your browser
- install to `~/.octra/wallet-generator` for future use
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
bun install
bun run build
bun start