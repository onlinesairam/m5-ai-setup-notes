# M5 MacBook Pro — AI Engineering Hub

Personal learning journal and setup tracker for building
a professional AI engineering workstation from scratch.

## Setup Progress

### Phase 0 — Mac Foundation ✅
- macOS hardened (FileVault, Firewall, Touch ID)
- Homebrew 5.0.15 installed (ARM-native /opt/homebrew)
- iTerm2 + Oh My Zsh configured
- zsh-autosuggestions + zsh-syntax-highlighting active
- PATH precedence fixed (Homebrew over Apple system binaries)

### Phase 1 — Productivity Tools ✅  
- Adobe Acrobat Reader
- Google Chrome + extensions
- Obsidian (knowledge base)
- Loom (demo recordings)
- Notion

### Phase 2 — Developer Infrastructure 🔄
- Git 2.53.0 (Homebrew) ✅
- GitHub SSH + CLI authenticated ✅
- Python (pyenv + Miniconda) ⬜
- Docker Desktop ⬜
- Kubernetes (k3d) ⬜
- Node.js (nvm) ⬜

### Phase 3 — AI Coding Tools ⬜
### Phase 4 — Local AI Stack ⬜
### Phase 5 — Agentic AI ⬜
### Phase 6 — AIOps & MLOps ⬜

## Key Concepts Learned

| Concept | Context |
|---|---|
| PATH precedence | Homebrew vs Apple system Git |
| .zprofile vs .zshrc | Login shell vs interactive shell |
| exec zsh | Replace shell process vs source |
| Idempotency | Why duplicate PATH lines appeared |
| OAuth device flow | gh auth login timeout issue |
| PAT vs GitHub App tokens | Copilot token in security log |
| ed25519 vs RSA | Modern SSH key algorithm |
| mkdir -p | Create full directory path at once |

## Commands Reference

\`\`\`bash
# Shell
exec zsh                    # fresh shell process
source ~/.zshrc             # reload config in current session
type -a <command>           # show all locations for a command

# Git
git config --list           # show all git configuration
ssh -T git@github.com       # verify SSH auth to GitHub
gh auth status              # verify GitHub CLI auth

# Homebrew  
brew doctor                 # system health check
brew list                   # show installed packages
brew upgrade                # update all packages
\`\`\`
