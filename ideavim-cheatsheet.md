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

---

## Search & Find

| Key | Action |
|-----|--------|
| `<leader>f<space>` | Search Everywhere |
| `<leader>ff` | Go to File |
| `<leader>fa` | Go to Action |
| `<leader>fc` | Go to Class |
| `<leader>fs` | Go to Symbol |
| `<leader>ft` | Find in Path (text search) |
| `<leader>/` | Find in current file |
| `<leader>sw` | Search word under cursor (forward) |
| `<leader>sW` | Search word under cursor (backward) |
| `n/N` | Next/previous result (centered) |

---

## Buffer / Tab Navigation

| Key | Action |
|-----|--------|
| `<S-L/H>` | Next/previous tab |
| `<leader>s` | Switcher popup |
| `<leader>bd` | Close current tab |
| `<leader><tab>l` | Last tab |
| `<leader><tab>f` | First tab |
| `<leader>`` | Switch to previous tab |

---

## Code Navigation

| Key | Action |
|-----|--------|
| `gd` | Go to Declaration |
| `gi` | Go to Implementation |
| `gt` | Go to Type Declaration |
| `gs` | Go to Super Method/Class |
| `gu` | Find Usages |
| `gR` | Rename Element |
| `K` | Quick Implementations |

---

## File Navigation

| Key | Action |
|-----|--------|
| `<leader>e` | Reveal in File Explorer |
| `<leader>fn` | New File |
| `<leader>sm` | Show Bookmarks |

---

## Navigation: Bracket Keys (`[ ]`)

| Key | Action |
|-----|--------|
| `[m / ]m` | Previous/next method |
| `[e / ]e` | Previous/next error |
| `[w / ]w` | Previous/next warning |
| `[/ / ]/` | Previous/next search match |
| `[b / ]b` | Previous/next bookmark |
| `[c / ]c` | Previous/next change |
| `]t` | Go to next todo |

---

## LSP / Code Actions

| Key | Action |
|-----|--------|
| `<leader>ca` | Generate code (constructors, getters, etc.) |
| `<leader>cf` | Reformat Code |
| `<leader>cd` | Show Error Description |

---

## Refactoring

| Key | Action |
|-----|--------|
| `<leader>re` | Refactorings menu |
| `<leader>rc` | Extract Method |
| `<leader>ri` | Introduce Variable |
| `<leader>rf` | Inline |

---

## Git

| Key | Action |
|-----|--------|
| `<leader>gg` | Open VCS tool window |
| `<leader>gc` | Commit |
| `<leader>gP` | Push |
| `<leader>gp` | Pull |
| `<leader>gf` | Fetch |
| `<leader>gu` | Update Project |
| `<leader>gb` | Branches |
| `<leader>gd` | Diff against last version |
| `<leader>gD` | Compare Files |
| `<leader>gl` | Git Log |

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
| `<leader>r<space>` | Choose Run Configuration |
| `<leader>rr` | Run |
| `<leader>rd` | Debug |
| `<leader>rt` | Run All Tests |
| `<leader>rm` | Run Maven Goal |
| `<leader>rq` | Stop |

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
| `<leader>tv` | New vertical terminal tab |
| `<leader>th` | New horizontal terminal tab |

---

## Quick Fixes / Diagnostics

| Key | Action |
|-----|--------|
| `<leader>xx` | Inspect Code |
| `<leader>xX` | Show Errors |
| `<leader>xq` | Problems view |

---

## UI Toggles

| Key | Action |
|-----|--------|
| `<leader>ul` | Toggle line numbers |
| `<leader>uL` | Toggle relative line numbers |
| `<leader>uw` | Toggle word wrap |
| `<leader>uh` | Toggle rendered documentation |
| `<leader>ui` | File Structure popup |

---

## General IDE

| Key | Action |
|-----|--------|
| `<leader>qq` | Exit |
| `<leader>qQ` | Quit all |

---

## Comments

| Key | Action |
|-----|--------|
| `gcc` | Toggle line comment |
| `gc` | Toggle comment (visual mode) |
| `gco` | Add comment below |
| `gcO` | Add comment above |

---

## Visual Mode

| Key | Action |
|-----|--------|
| `< / >` | Indent/unindent (stay in visual) |

---

## Insert Mode

| Key | Action |
|-----|--------|
| `, . ;` | Create undo break point |

---

## Java

| Key | Action |
|-----|--------|
| `<leader>rj` | Run class |
| `<leader>rdj` | Debug class |
