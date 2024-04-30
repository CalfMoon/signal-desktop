<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/signalapp/Signal-Desktop">Signal Desktop</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/CalfMoon/signal-desktop/stargazers"><img src="https://img.shields.io/github/stars/CalfMoon/signal-desktop?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/CalfMoon/signal-desktop/issues"><img src="https://img.shields.io/github/issues/CalfMoon/signal-desktop?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/CalfMoon/signal-desktop/contributors"><img src="https://img.shields.io/github/contributors/CalfMoon/signal-desktop?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/mocha.webp"/>
</details>

## Status
The project in its current state is in no way complete. [TODO](TODO.md) file contains the list of things completed and remaining to complete.

## Usage

### Windows
1. Install 7-zip and its asar7z plugin.
2. Open `C:\Users\user_name\AppData\Local\Programs\signal-desktop\resources\app.asar` with 7zip.
3. Go into stylesheets directory.
4. Copy the theme you want to use into the directory.
5. Right click and edit `manifest.css` file and add import statement at the top. `@import "catppuccin-<flavour>.css";` Replace `<flavour>` with flavour you want to use.
6. Save and close your editor.
7. Enjoy!

### Linux
1. Install npm's asar package globally. `sudo npm install -g @electron/asar`
2. Extract asar into a temporary directory and change directory. `asar e /usr/lib/signal-desktop/resources/app.asar temp/ && cd temp/stylesheets`
3. Copy and paste theme you want to use into current directory.
4. Add import statement at the top of `manifest.css` file. `@import "catppuccin-<flavour>.css";` Replace `<flavour>` with flavour you want to use.
5. Remove the temp directory.
6. Enjoy!

## 💝 Thanks to

- [CalfMoon](https://github.com/CalfMoon)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
