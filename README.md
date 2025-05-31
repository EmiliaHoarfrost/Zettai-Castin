# ZettaiCastin

**ZettaiCastin** is an interactive web-based note-taking application using a map interface.
Inspired by the **Zettelkasten** method, it allows users to pin and write notes on specific geographic locations.
Zettai for absolute in Japanese.

Built with:

- 🗺️ [Leaflet.js](https://leafletjs.com/) for map rendering  
- 🎨 [Tailwind CSS](https://tailwindcss.com/) for styling  
- 🧠 Vanilla **JavaScript**
 
## <picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4f8/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4f8/512.gif" alt="📸" width="32" height="32">
</picture> Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/8153eeba-9278-4d39-9b29-06354adc6e5d" alt="Screenshot 1" width="800" style="border-radius: 12px;"><br><br>
  <img src="https://github.com/user-attachments/assets/856fef36-7cd7-4a0b-a94a-9822fd360105" alt="Screenshot 2" width="800" style="border-radius: 12px;"><br><br>
  <img src="https://github.com/user-attachments/assets/9a357997-06f9-4e41-b566-9f6ea2f8531c" alt="Screenshot 3" width="800" style="border-radius: 12px;"><br><br>
  <img src="https://github.com/user-attachments/assets/9d137ee8-71b1-4d69-8316-ad18fe9dce0f" alt="Screenshot 4" width="800" style="border-radius: 12px;">
</p>



## ✨ Features

- 🖱️ Click on the map to move around real-world locations at global & local scales.
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

## 🚀 Getting Started

You can find an online version at zettaicastin.42dev.io (unsecure port 80 HTTP connection, can cause issues with some browsers),
otherwise just open the `index.html` file in a web browser.
No build process or server is required!

### 📂 Project Structure

```text
index.html         # Main HTML with embedded JavaScript and Tailwind CSS
