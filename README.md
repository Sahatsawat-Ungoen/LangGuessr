# LangGuessr – Text Language Detection CLI
LangGuessr is a simple command-line tool that detects the language of a given text using franc, langs, and colors.js. It provides accurate language identification with clear, color-coded feedback.
## 🚀 Features 
✔️ Detects language from input text ✔️ Displays language name based on ISO 639-3 code ✔️ Color-coded output for better readability
## 🔧 Installation
Install dependencies:
```` bash
npm install franc langs colors
````
## 📝 Usage
Run the script with a text sample:
```` bash
node index.js "Bonjour tout le monde"
````
Output:
```` bash
Our best guess is: French
````
If the language is unclear, it suggests adding more text:
````bash
SORRY, COULDN'T FIGURE IT OUT! TRY WITH MORE SAMPLE TEXT!
````
