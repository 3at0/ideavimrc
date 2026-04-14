# IntelliJ IdeaVim Cheatsheet

## Leader Key: `<space>`

---

## General

| Key | Action |
|-----|--------|
| `<C-h/j/k/l>` | Navigate left/down/up/right in insert mode |
| `<C-d>` | Scroll down and center |
| `<C-u>` | Scroll up and center |
| `<C-s>` | Save |
| `<esc>` | Clear search highlight |
| `j/k` | Move down/up (respects wrapped lines) |
| `<M-S-J/K>` | Jump 10 lines down/up |
| `<M-S-H/L>` | Beginning/end of line |
| `<M-S-Y/P>` | Yank/paste to system clipboard |
| `<M-S-W>` | Close current buffer/tab |

---

## Search

| Key | Action |
|-----|--------|
| `/` | Find |
| `n/N` | Next/previous search result (centered) |
| `<leader>sw` | Search word under cursor |
| `<leader>sW` | Search word under cursor (backward) |
| `<leader>sg` / `<leader>fg` | Find in Path (full text search) |
| `<leader>sf` | Search Everywhere |

---

## Navigation

| Key | Action |
|-----|--------|
| `<S-L/H>` | Next/previous tab |
| `[b / ]b` | Previous/next buffer |
| `<leader><tab>l` | Last tab |
| `<leader><tab>f` | First tab |
| `<leader>`` | Switch to previous tab |
| `gd` | Go to Declaration |
| `gi` | Go to Implementation |
| `gr` | Find Usages |
| `gR` | Rename Element |
| `K` | Quick Implementations |
| `<leader>ff` | Go to File |
| `<leader>fn` | New File |
| `<leader>e` | Reveal in File Explorer |

---

## LSP / Code Actions

| Key | Action |
|-----|--------|
| `<leader>ca` | Generate code (constructors, getters, etc.) |
| `<leader>cf` | Reformat Code |
| `<leader>cd` | Show Error Description |

---

## Navigation: Bracket Keys (`[ ]`)

| Key | Action |
|-----|--------|
| `[m / ]m` | Previous/next method |
| `[M / ]M` | Previous/next method (alternate) |
| `[e / ]e` | Previous/next error |
| `[w / ]w` | Previous/next warning |
| `[/ / ]/` | Previous/next search match |
| `[b / ]b` | Previous/next bookmark |
| `[c / ]c` | Previous/next change |
| `[t / ]t` | Go to todo |

---

## Debugging

| Key | Action |
|-----|--------|
| `<F5>` | Debug |
| `<F6>` | Toggle Line Breakpoint |
| `<F7>` | Step Into |
| `<F8>` | Step Over |
| `<F9>` | Step Out |
| `<F10>` | Rerun |
| `<F12>` | Stop |
| `<leader>db` | Toggle Breakpoint |

---

## Running

| Key | Action |
|-----|--------|
| `<leader>rr` | Run |
| `<leader>rd` | Debug |
| `<leader>rt` | Run All Tests |
| `<leader>rm` | Run Maven Goal |
| `<leader>rq` | Stop |

---

## Git

| Key | Action |
|-----|--------|
| `<leader>gc` | Commit |
| `<leader>gp` | Pull |
| `<leader>gC` | Push |
| `<leader>gb` | Git Blame |
| `<leader>gd` | Show Diff |
| `<leader>gD` | Compare Files |

---

## Windows / Splits

| Key | Action |
|-----|--------|
| `<leader>-` | Split horizontally |
| `<leader>\|` | Split vertically |
| `<leader>wd` | Close all editors |
| `<leader>wm` | Maximize editor |

---

## Terminal

| Key | Action |
|-----|--------|
| `<leader>tt` | Open terminal |
| `<leader>tv` | New vertical terminal |
| `<leader>th` | New horizontal terminal |

---

## Refactoring

| Key | Action |
|-----|--------|
| `<leader>re` | Refactorings menu |
| `<leader>rc` | Extract Method |
| `<leader>ri` | Introduce Variable |
| `<leader>rf` | Inline |

---

## Comments

| Key | Action |
|-----|--------|
| `gcc` | Toggle line comment |
| `gc` | Toggle block comment (visual mode) |
| `gco` | Add comment below |
| `gcO` | Add comment above |

---

## UI Toggles

| Key | Action |
|-----|--------|
| `<leader>ul` | Toggle line numbers |
| `<leader>uL` | Toggle relative line numbers |
| `<leader>uw` | Toggle word wrap |
| `<leader>uh` | Toggle rendered documentation |

---

## Quick Fixes / Diagnostics

| Key | Action |
|-----|--------|
| `<leader>xx` | Inspect Code |
| `<leader>xX` | Show Errors |
| `[q / ]q` | Previous/next error |
| `<leader>xq` | Problems view |

---

## General IDE

| Key | Action |
|-----|--------|
| `<leader>ui` | File Structure |
| `<leader>sh` | Help |
| `<leader>sk` | Keymap |
| `<leader>sm` | Show Bookmarks |
| `<leader>qq` | Exit |
| `<leader>qQ` | Quit all |

---

## Visual Mode

| Key | Action |
|-----|--------|
| `< / >` | Indent/unindent (stay in visual) |

---

## Insert Mode

| Key | Action |
|-----|--------|
| `, . ;` | Undo points after typing |

---

## Java (Optional)

| Key | Action |
|-----|--------|
| `<leader>rj` | Run class |
| `<leader>rdj` | Debug class |

---

## Rust (Optional, requires Rust plugin)

| Key | Action |
|-----|--------|
| `<leader>rc` | Cargo Run |
| `<leader>rt` | Cargo Test |
| `<leader>rb` | Cargo Build |
