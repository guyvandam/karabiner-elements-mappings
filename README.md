# Karabiner-Elements mappings ⌨️

key remappings for [Karabiner Elements](https://karabiner-elements.pqrs.org/).

# 🚀 "installation" 

1. *general Karabiner elements setup (install, give permissions, etc..)*
2. press *`add your own rule`*
![image](images/adding-modification.png)
3. copy & paste the desired modification(s)

# 🔗 mappings

## navigation

| shortcut | action | vi-style | macOS-native |
|---|---|:---:|:---:|
| `⌥⌘ ←/→/↑/↓` | Move between desktops | | ✅ |
| `⌥ h/j/k/l` | Arrow keys (left/down/up/right) | ✅ | |
| `⌥ b` | Jump to beginning of word | ✅ | |
| `⌥ e` | Jump to end of word | ✅ | |
| `⌥ u` | Jump to start of line | | |
| `⌥ i` | Jump to end of line | | |

## editing

| shortcut | action | vi-style | macOS-native |
|---|---|:---:|:---:|
| `⌥ ⌫` | Forward delete word | | ✅ |
| `⌥ ⇧ ⌫` | Forward delete to end of line | | ✅ |

---

# modification files

| file | description |
|---|---|
| [`modifications/option-command-arrow→move-desktops.json`](./modifications/option-command-arrow→move-desktops.json) | Move between desktops with `⌥⌘` + arrow keys (or `hjkl`) |
| [`modifications/vi-option+hjkl→arrow-keys.json`](./modifications/vi-option+hjkl→arrow-keys.json) | `⌥hjkl` as arrow keys |
| [`modifications/option-backspace→forward-delete.json`](./modifications/option-backspace→forward-delete.json) | `⌥⌫` forward-deletes a word; `⌥⇧⌫` deletes to end of line |
| [`modifications/vi-option-b-e→word-start-end.json`](./modifications/vi-option-b-e→word-start-end.json) | `⌥b` / `⌥e` jump to start / end of word |
| [`modifications/option-u-i→line-start-end.json`](./modifications/option-u-i→line-start-end.json) | `⌥u` / `⌥i` jump to start / end of line |
