# Time Capsule

Time Capsule is a powerful tool designed to continuously capture and store your digital activities, creating a comprehensive digital memory. It provides a core system for data management with a web interface for interaction and optional plugins for various data capture methods.

## ✨ Current Features
1. AI-Enhanced Time Capsules
	•	AI Time Restoration: Enhance old or low-quality photos/videos using AI-powered upscaling, colorization, and restoration.
	•	Future Self Predictions: AI generates future-aged versions of users’ photos and videos to simulate how they might look in 10, 20, or 50 years.
	•	AI Memory Compilation: Automatically creates nostalgic video montages with music, captions, and personalized highlights from stored memories.

2. Smart Media Organization
	•	AI Content Sorting: Automatically tags, categorizes, and organizes photos/videos based on faces, locations, events, and emotions.
	•	Memory Search: Users can search for memories using natural language (e.g., “Show me my birthday pictures from 2018”).
	•	Smart Recap: AI summarizes long videos into short highlight reels using facial recognition and scene detection.

3. Interactive AI Features
	•	AI Storytelling Mode: Converts photos and videos into narrated stories with AI-generated voiceovers and contextual details.
	•	AI-Powered Reactions: AI suggests captions, hashtags, and emojis based on the emotions detected in the media.
	•	Deepfake Time Travel: Users can merge their past and present selves into a single video conversation using AI.

4. Social & Engagement Features
	•	AI-Powered Time Capsules: Users can send AI-generated messages that simulate their voice and thoughts for future delivery.
	•	Interactive AI Avatars: Users create AI avatars that evolve over time and can send pre-recorded messages in a future-simulated voice.
AI-Generated Reunions: The app suggests the best times for friends/family to reconnect based on past interactions and schedules.

5. Privacy & Security Features
	•	AI Anonymization: Users can blur faces or remove sensitive details before sharing.
	•	AI-Powered Access Control: AI verifies identity before unlocking time capsules (voice, face, or behavior-based authentication).
	•	AI Memory Vault: Encrypts time capsules with AI-driven security, ensuring only authorized users can access them.

- 🎙️ Real-time microphone recording
- 🗣️ Speech-to-text transcription using Fast-Whisper library
- 💾 Database storage of transcribed text using Chroma vector database
- 🔌 Plugin system for extensibility
- ⚙️ Configurable settings via JSON configuration file
- 🖥️ Web interface for managing plugins and starting the application
- 📊 Transcription service for processing audio recordings
- 🌐 Flask-based web server for handling HTTP requests and responses
- 🔄 Real-time status updates including CPU, memory, and disk usage

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

4. Configure settings in `config.json` according to your preferences.

## 🖥️ Usage

Start the Time Capsule application:

```bash
python main.py
```

The application will start and display the URL for accessing the web interface. Use this interface to manage plugins and control the Time Capsule.

Press `Ctrl+C` in the terminal to initiate a graceful shutdown of the application.

## 🧩 Plugin System

Time Capsule uses a plugin system for extensibility. Plugins are located in the `plugins` directory. Each plugin should be in its own subdirectory and contain a main class that matches the plugin name.

To create a new plugin:

1. Create a new directory in the `plugins` folder with your plugin name.
2. Create a Python file with the same name as your plugin.
3. Implement the main plugin class with `start()` and `stop()` methods.

Plugins can be enabled or disabled through the web interface or by modifying the `config.json` file.

## 🔧 Configuration

The `config.json` file contains various settings for the application, including:

- Database path
- Audio recording settings
- Transcription settings
- Plugin states
- Web interface refresh interval

Modify this file to customize the behavior of Time Capsule.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any questions, suggestions, or feedback, please feel free to reach out to me on X at [@TheSethRose](https://www.x.com/TheSethRose)

## ❤️ Support

<a href="https://www.buymeacoffee.com/TheSethRose" target="_blank"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee!&emoji=&slug=TheSethRose&button_colour=000000&font_colour=ffffff&font_family=Cookie&outline_colour=ffffff&coffee_colour=FFDD00" alt="Buy Me A Coffee!"></a>

## ⚠️ Disclaimer

Ensure compliance with all applicable laws and regulations when using this software, particularly regarding privacy and data protection. Time Capsule captures and stores personal data, so use it responsibly and with proper consent.
