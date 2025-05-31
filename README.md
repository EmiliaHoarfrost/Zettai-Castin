# Zettai-Castin

**Zettai-Castin** is an interactive web-based note-taking application using a map interface. Inspired by the **Zettelkasten** method, it allows users to pin and write notes on specific geographic locations.

Built with:

- 🗺️ [Leaflet.js](https://leafletjs.com/) for map rendering  
- 🎨 [Tailwind CSS](https://tailwindcss.com/) for styling  
- 🧠 Vanilla JavaScript  
- 📝 [Marked.js](https://marked.js.org/) for Markdown rendering

## ✨ Features

- 🖱️ Click on the map to create notes at real-world locations.
- 📝 Edit and store rich text notes using Markdown.
- 📦 Save and export your notes as GeoJSON, JSON, or plain text.
- 📁 Import existing notes from `.json` or `.txt` files.
- 🔄 Toggle between standard and satellite map views.
- 💾 Auto-saving of notes to local storage.
- 🧭 Keyboard shortcuts for navigation and actions.

## 🧭 Keyboard Shortcuts

| Key | Action                          |
|-----|---------------------------------|
| `W` | Add a note at cursor location   |
| `X` | Delete the selected note        |
| `C` | Clear all notes                 |
| `S` | Toggle Satellite view           |
| `M` | Switch to Map tab               |
| `L` | Switch to Log tab               |
| `A` | Switch to About tab             |

## 📷 Screenshots

<!-- Add screenshot images if available -->
_(Coming soon...)_

## 🚀 Getting Started

You can find an online version at zettaicastin.42dev.io,
otherwise just open the `index.html` file in a web browser.
No build process or server is required!

### 📂 Project Structure

```text
index.html         # Main HTML with embedded JavaScript and Tailwind CSS
