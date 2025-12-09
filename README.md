# 🌅 zedlight for iTerm2

A clean, light color scheme for [iTerm2](https://iterm2.com), inspired by [Zed Editor](https://zed.dev)'s One Light theme and the original [Atom One Light](https://github.com/atom/one-light-syntax).

## ✨ Features

- Light theme optimized for daytime use
- High contrast for readability
- Carefully selected ANSI colors
- Based on the proven Atom/Zed One Light palette

## 📦 Installation

### Manual

1. Download [`zedlight.itermcolors`](./zedlight.itermcolors)
2. Open iTerm2 → **Preferences** (`⌘,`)
3. Go to **Profiles** → **Colors**
4. Click **Color Presets...** → **Import...**
5. Select the downloaded `zedlight.itermcolors` file
6. Click **Color Presets...** → **zedlight**

### Via curl

```bash
curl -Lo ~/Downloads/zedlight.itermcolors \
  https://raw.githubusercontent.com/your-username/zedlight-iterm2/main/zedlight.itermcolors
```

Then import via iTerm2 Preferences.

## 🎨 Color Palette

The palette is derived from [Atom One Light](https://github.com/atom/one-light-syntax/blob/master/styles/colors.less) and [One Half](https://github.com/sonph/onehalf).

### ANSI Colors

| Color          | Normal    | Bright    |
|----------------|-----------|-----------|
| Black          | `#383A42` | `#696C77` |
| Red            | `#E45649` | `#CA1243` |
| Green          | `#50A14F` | `#50A14F` |
| Yellow         | `#C18401` | `#986801` |
| Blue           | `#0184BC` | `#4078F2` |
| Magenta        | `#A626A4` | `#A626A4` |
| Cyan           | `#0997B3` | `#0184BC` |
| White          | `#FAFAFA` | `#FFFFFF` |

### UI Colors

| Element        | Hex       |
|----------------|-----------|
| Background     | `#FAFAFA` |
| Foreground     | `#383A42` |
| Bold           | `#383A42` |
| Selection      | `#BFCEFF` |
| Cursor         | `#526FFF` |
| Cursor Text    | `#FAFAFA` |
| Links          | `#0184BC` |

### Syntax Mapping (HSL Reference)

```
Cyan    → hsl(198, 99%, 37%)  → #0184BC
Blue    → hsl(221, 87%, 60%)  → #4078F2
Purple  → hsl(301, 63%, 40%)  → #A626A4
Green   → hsl(119, 34%, 47%)  → #50A14F
Red     → hsl(  5, 74%, 59%)  → #E45649
Orange  → hsl( 41, 99%, 38%)  → #986801
```

## 🖼️ Screenshots

<img width="1562" height="1029" alt="Screenshot 2025-12-08 at 23 21 59" src="https://github.com/user-attachments/assets/ad11bda2-2b96-4b69-8913-af35bc156646" />


## 🙏 Inspirations

- [Atom One Light](https://github.com/atom/one-light-syntax) — Original color palette
- [Zed Editor](https://zed.dev) — Theme implementation reference
- [One Half](https://github.com/sonph/onehalf) — Terminal color adaptation

## 📚 References

- [Atom One Light - colors.less](https://github.com/atom/one-light-syntax/blob/master/styles/colors.less)
- [Zed Theme Documentation](https://zed.dev/docs/themes)
- [Zed One Theme Source](https://github.com/zed-industries/zed/blob/main/assets/themes/one/one.json)

## 📄 License

[MIT](LICENSE)
