# speech-based-search-engine
📌 Objective:
This script implements a simple voice-controlled search engine using Python. It listens to a user's spoken query and automatically opens a web browser with the search results.

🛠️ Technologies & Libraries:
speech_recognition – Converts speech to text.

pyttsx3 – Text-to-speech (TTS) for system voice responses.

webbrowser – Opens URLs in the default web browser.

🚀 How It Works:
Initialize TTS Engine: Sets up the pyttsx3 engine for speaking back to the user.

Take Voice Command:

Listens to the user via microphone.

Converts speech to text using Google’s speech recognition API.

Search Web:

If speech is successfully recognized, it performs a Google search with the spoken text.

Opens the search results in the default web browser.

🧠 Key Functions:
speak(text): Speaks a given string out loud.

take_command(): Captures and transcribes spoken input.

search_web(query): Opens Google with the transcribed query.

📝 Example Use:
Run the script and say something like "latest news about AI". The system will open a Google search for that phrase.

⚠️ Notes:
Requires an active internet connection for speech recognition.

May need microphone permissions.

Error handling included for unrecognized speech and service issues.
