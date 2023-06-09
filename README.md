<h1>🎙️ Dicis - Text to Speech Service 🗣️</h1>
<p>This project is a Python-based 🐍 text-to-speech converter that uses the Microsoft Cognitive Services API. Given text input file, it generates audio files in mp3 format. It's designed to be simple to use, efficient, and modular. 🎧</p>
<h2>🔥 Features</h2>
<ul>
  <li>🔄 Converts text to speech using Microsoft Cognitive Services API</li>
  <li>🎛️ Allows choice of voice (RaquelNeural or FernandaNeural)</li>
  <li>⏱️ Retries on failure with exponential backoff</li>
  <li>🗂️ Saves audios in an organized structure</li>
  <li>✍️ Requires text to be placed in a `sentences.txt` file for processing</li>
</ul>
<h2>📥 Installation</h2>
<p>Clone the repository to your local machine:</p>
<pre>
<code>
git clone https://github.com/GabrielAgrela/Dicis.git
</code>
</pre>
<p>Install the necessary Python packages:</p>
<pre>
<code>
pip install -r requirements.txt
</code>
</pre>
<p>Ensure you have the required environment variables set up:</p>
<ul>
  <li>🔑 `API_KEY` : Your Microsoft Cognitive Services API key</li>
  <li>🌐 `REGION` : Your service region</li>
</ul>
<p>These can be set in a `.env` file in the project root:</p>
<pre>
<code>
API_KEY=your_api_key
REGION=your_region
</code>
</pre>
<h2>🛠️ Usage</h2>
<p>Place the sentences that you want to convert to speech in the `sentences.txt` file. Then, run the main script and follow the prompts:</p>
<pre>
<code>
python main.py
</code>
</pre>
<p>Alternatively, for those not wanting to run Python scripts, a precompiled executable is available in the releases tab on the GitHub page. Just download and run the `.exe` file.</p>
<h2>🤝 Contributing</h2>
<p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.🔧</p>
<p>Please make sure to update tests as appropriate.✅</p>
<h2>📜 License</h2>
<p><a href="https://choosealicense.com/licenses/mit/">MIT</a></p>
