# Time Capsule

Time Capsule is a powerful tool designed to continuously capture and store your digital activities, creating a comprehensive digital memory. It provides a core system for data management with plans to expand to a web interface for interaction and optional plugins for various data capture methods.

## ✨ Current Features

- 🎙️ Real-time microphone recording
- 🗣️ Speech-to-text transcription using Fast-Whisper library
- 💾 Database storage of transcribed text using Chroma vector database
- 🔌 Plugin system for extensibility
- ⚙️ Configurable settings via JSON configuration file
- 🖥️ Interactive CLI menu for managing plugins and starting the application
- 📊 Transcription service for processing audio recordings

## 🚀 Future Features

For a detailed list of planned features, please see our [TODO list](TODO.md).

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TheSethRose/Time-Capsule.git
   cd Time-Capsule
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure settings in `config/config.json` according to your preferences.

## 🖥️ Usage

Start Time Capsule application:

```bash
python main.py
```

Use the interactive menu to manage plugins and start Time Capsule.

Press `Ctrl+C` to stop the application.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any questions, suggestions, or feedback, please feel free to reach out to me on X at [@TheSethRose](https://www.x.com/TheSethRose)

## ❤️ Support

<a href="https://www.buymeacoffee.com/TheSethRose" target="_blank"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee!&emoji=&slug=TheSethRose&button_colour=000000&font_colour=ffffff&font_family=Cookie&outline_colour=ffffff&coffee_colour=FFDD00" alt="Buy Me A Coffee!"></a>

## ⚠️ Disclaimer

Ensure compliance with all applicable laws and regulations when using this software, particularly regarding privacy and data protection.
