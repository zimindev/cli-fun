## 🎨 Cool Terminal Animation Tools (CLI Eye Candy)

Bring your terminal to life with these fun and aesthetic command-line tools — perfect for minimal setups like i3wm or just for fun! 😎

---

### 1. 🧪 `cmatrix` – Matrix Code Rain

Simulates the iconic falling green characters from *The Matrix*.

```bash
sudo pacman -S cmatrix
cmatrix -C green
```

🔧 **Options:**

* `-C [color]` – change color (red, blue, white, etc.)
* `-s` – slow scroll
* `-b` – bold characters

---

### 2. 🧩 `pipes.sh` – Terminal Pipes Screensaver

Animated, colorful pipes grow across your terminal like a screensaver.

```bash
sudo pacman -S pipes.sh
pipes.sh
```

🔧 **Options:**

* `-t` – thinner lines
* `-p 4` – number of pipes
* `-R` – random colors

---

### 3. 🐠 `asciiquarium` – ASCII Aquarium

Animated fish, submarines, and sea bubbles — in pure ASCII art.

```bash
yay -S asciiquarium
asciiquarium
```

⚠️ Requires: `perl` + `Term::Animation` (auto-installed from AUR)

---

### 4. 🚂 `sl` – Steam Locomotive

Misspelled `ls`? Surprise! Here comes a steam locomotive in your terminal.

```bash
sudo pacman -S sl
sl
```

🔧 **Options:**

* `-a` – crash animation (accident)
* `-l` – smaller train
* `-F` – force run
* `-e` – sound (if supported)

---

### 5. 🕒 `tty-clock` – Terminal Clock

Minimal, large, digital clock in your terminal window.

```bash
sudo pacman -S tty-clock
tty-clock -s -c -C 4
```

🔧 **Options:**

* `-s` – show seconds
* `-c` – center the clock
* `-C` – set color (1–7)

---

### 6. 🔥 `cacafire` – ASCII Fire

Generates a blazing fire animation in ASCII using libcaca.

```bash
sudo pacman -S libcaca
cacafire
```

⚠️ Best viewed in XTerm-compatible terminals.

---

### 7. 🐱 `oneko` – Cat Follows Cursor (X11)

A cute cat that chases your mouse cursor across the screen.

```bash
yay -S oneko
oneko
```

📌 X11 only (does not work in tty or Wayland).

---

### 8. 🔥 `aafire` – ANSI Fire (Lightweight Alt)

Another fire animation, simpler and faster with AAlib.

```bash
sudo pacman -S aview
aafire
```

---

### 9. 📖 `glow` – Markdown Viewer in Terminal

Renders Markdown beautifully right inside your terminal.

```bash
sudo pacman -S glow
glow README.md
```

📚 Supports local files and GitHub READMEs.

---

### 10. 🖼️ `chafa` – Image to ASCII Art

Convert images to colorful ASCII art. Supports 256 colors, truecolor, sixel, etc.

```bash
sudo pacman -S chafa
chafa image.png
```

---

## ✨ Bonus Picks:

* 🐱 `nyancat` – classic rainbow cat flying across your terminal
* 🌱 `cbonsai` – grows beautiful ASCII bonsai trees
* 📟 `neofetch` / `ufetch` – show system info with style
* 📦 `boxes` – draw ASCII boxes around text
* 🌈 `lolcat` – rainbow colorizes any output (`echo Hello | lolcat`)
