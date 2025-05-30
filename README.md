# st - simple terminal

st is a minimalistic terminal emulator.

## Quick start

st depends on libX11, fontconfig and libXft.

```shell
# on fedora
sudo dnf install libX11-devel libXft-devel fontconfig-devel
sudo make clean install
```

## Patches applied

- [anysize](https://st.suckless.org/patches/anysize)
- [scrollback (ringbuffer version)](https://st.suckless.org/patches/scrollback)

## My additions

### Keymaps

- `Ctrl-Shift-c` for copying selected text
- `Ctrl-Shift-v` for pasting
- `Ctrl-Shift-k` for scrolling up
- `Ctrl-Shift-j` for scrolling down
- `Ctrl-+/-` to increase/decrease font size
- `Ctrl-=` to make font default size (19)

---

### Colorscheme

Applied regular soft colorscheme with dark background.
