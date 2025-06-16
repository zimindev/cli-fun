## 🎨 Cool Terminal Animation Tools (CLI Eye Candy)

Here’s a list of fun and aesthetic CLI tools that bring your terminal to life — great for dotfile lovers, minimal setups like i3wm, or just nerdy fun.

---

### 1. `cmatrix` – Matrix Code Rain

Simulates the green digital rain from *The Matrix*.

```bash
sudo pacman -S cmatrix
cmatrix -C green
```

**Options:**

* `-C [color]` – change color (e.g., red, blue, white)
* `-s` – slow scroll
* `-b` – bold characters

---

### 2. `pipes.sh` – Terminal Pipes Screensaver

Draws random colored pipe paths across your terminal.

```bash
sudo pacman -S pipes.sh
pipes.sh
```

**Options:**

* `-t` – thinner lines
* `-p 4` – number of pipes
* `-R` – random colors

---

### 3. `asciiquarium` – Animated ASCII Aquarium

A fun, animated aquarium with fish, submarines, and bubbles.

```bash
yay -S asciiquarium
asciiquarium
```

> Requires Perl + `Term::Animation`

---

### 4. `sl` – Steam Locomotive

A humorous ASCII train that chugs across your screen if you mistype `ls`.

```bash
sudo pacman -S sl
sl
```

**Options:**

* `-a` – accident/crash
* `-l` – smaller train
* `-F` – force run
* `-e` – sound (if available)

---

### 5. `tty-clock` – Terminal Clock

A sleek digital clock for your terminal.

```bash
sudo pacman -S tty-clock
tty-clock -s -c -C 4
```

**Options:**

* `-s` – seconds
* `-c` – center
* `-C [color]` – color (1–7)

---

### 6. `cacafire` – ASCII Fire Animation

Creates a fire animation in ASCII characters using libcaca.

```bash
sudo pacman -S libcaca
cacafire
```

> Requires an XTerm-compatible terminal to render properly.

---

### 7. `oneko` – Cat Chasing Mouse Cursor (X11)

A cute cat that follows your mouse cursor around the screen.

```bash
yay -S oneko
oneko
```

> Works only in X11 environments (not in pure tty).

---

### 8. `aafire` – ANSI ASCII Fire (Alternative)

An alternative flame animation using AAlib.

```bash
sudo pacman -S aview
aafire
```

---

### 9. `glow` – Markdown Viewer in the Terminal

Not an animation, but beautifully renders Markdown in your terminal.

```bash
sudo pacman -S glow
glow README.md
```

---

### 10. `chafa` – Image to ASCII Art Converter

Converts images to colorful or grayscale ASCII.

```bash
sudo pacman -S chafa
chafa image.png
```

Supports sixel, iTerm2 graphics, 256-color, etc.

---

## 💬 Bonus Suggestions:

* `nyancat` – rainbow cat flying across your terminal
* `cbonsai` – randomly growing ASCII bonsai trees
* `neofetch` / `ufetch` – system info with style
* `boxes` – draw ASCII boxes around your text
* `lolcat` – rainbow-colored output for any command
