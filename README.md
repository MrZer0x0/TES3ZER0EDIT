
✨ Key Features
🚀 Zero Installation
Single File: The entire editor is contained within one HTML file.
Offline Ready: Works without an internet connection.
Cross-Platform: Runs on Windows, macOS, Linux, and even Android (via browser).
🛠 Powerful Editing Tools
Record Editing: Modify NPCs, Items, Spells, Game Settings (GMST), Globals, and more.
Header Editor: Easily change the file author, description, version, and master dependencies.
Script & Text: View and edit scripts and book text with syntax highlighting support.
JSON Support: Export plugins to human-readable JSON and import them back to binary ESP format.
⚙️ Built-in tes3cmd Emulation
Forget about command lines and Perl installations. TES3ZER0EDIT includes JavaScript implementations of popular tes3cmd functions:

Clean: Remove dirty edits and deleted records (AM, UDR).
Multipatch: Generate a merged patch to resolve conflicts between mods.
Fixit: Automatically repair common binary errors (chunk overflows, duplicate IDs).
Overdial: Detect and remove duplicate dialogue topics.
🇷🇺 Localization & Encoding Support
CP1251 Support: Fully compatible with the Russian (1C) version of Morrowind. The editor correctly handles Cyrillic encoding during parsing and saving.
Topic Fixer: Specialized tool to analyze and repair broken @Topic# hyperlinks in dialogue text, essential for localized versions of the game.
📖 How to Use
Download: Get the latest TES3ZER0EDIT.html from the Releases page.
Open: Double-click the file to open it in any modern web browser (Google Chrome, Edge, Firefox, etc.).
Load: Drag and drop your .esp or .esm file into the window (or use the "Open" button).
Edit: Select record types on the left, choose a record, and modify values on the right.
Save: Click Save ESP to download your modified plugin.
Note on Saving Dates: To preserve the original file modification date (timestamp), please use a Chromium-based browser (Chrome, Edge, Opera) as they support the File System Access API. Other browsers will save the file with the current date.

🤝 Compatibility
Supported Files: .esp, .esm, .ess (partial), .json (proprietary format).
Browsers: Chrome (Recommended), Edge, Firefox, Safari.
📦 Advanced Features
Master Handling: Load Morrowind.esm and other masters to correctly validate references in scripts and dialogues.
Book Reader: Preview in-game books with formatted HTML rendering.
Merge Plugins: Combine multiple plugins into one (basic implementation).
📝 License
Author: MrZer0

This project is free to use, distribute, and modify. Please credit the original author if you redistribute modified versions.

Disclaimer: This tool is not affiliated with Bethesda Softworks. Always backup your plugins before editing.
