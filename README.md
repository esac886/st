# st - simple terminal

st is a minimalistic terminal emulator.

## Quick start

st depends on libX11, fontconfig and libXft.

```shell
# on fedora
sudo dnf install libX11-devel libXft-devel fontconfig-devel
sudo make clean install
```

Also this version of st depends on Caskaydia Mono Nerd Font. This can be changed in `config.h` static variable.

## Patches applied

- [anysize (expected version)](https://st.suckless.org/patches/anysize)
- [scrollback](https://st.suckless.org/patches/scrollback)
- [glyph wide support](https://st.suckless.org/patches/glyph_wide_support)
- [font2](https://st.suckless.org/patches/font2)

## My additions

### Keymaps

- `Ctrl-Shift-c` for copying selected text
- `Ctrl-Shift-v` for pasting
- `Ctrl-Shift-k` for scrolling up by a screen
- `Ctrl-Shift-j` for scrolling down by a screen
- `Ctrl-↑` for scrolling up
- `Ctrl-↓` for scrolling down
- `Ctrl-+/-` to increase/decrease font size
- `Ctrl-=` to make font default size (20)

---

### Colorscheme

Applied regular soft colorscheme with dark background.
