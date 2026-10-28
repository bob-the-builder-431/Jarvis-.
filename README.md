J.A.R.V.I.S. 🚀  
Your AI assistant for macOS

Meet JARVIS: a Mac app that’s got a slick, Iron Man-style reactor HUD, smart voice conversations, Groq-powered AI, built-in web search, and a voice with all the charm of a British butler.

Download: Latest JARVIS release

⚡ Getting started
1. Grab the .dmg from the release page.
2. Open it. If your Mac asks, drag JARVIS to Applications.
3. Launch JARVIS.
4. Give it microphone access when prompted.
5. Fire up the HUD and start chatting.

JARVIS needs an internet connection—its AI and web search run online. If your Mac throws a security warning, don’t panic. Some builds aren’t signed or notarised yet.

✨ What JARVIS can do
- 🎙️ Voice chat — Talk to JARVIS and get answers back, read to you.
- 🧠 AI smarts — Fast, accurate, and calm thanks to Groq.
- 🌐 Web search — Ask for current info (with search set up).
- 🌍 Speak multiple languages — English, Indonesian, and Mandarin (native build).
- 🌀 Reactor HUD — A dark, sci-fi interface inspired by Iron Man.
- 🔔 Update alerts — JARVIS can let you know when new releases are out.

Features might vary by build. Updates are not fully automatic—yet.

🎤 Talking with JARVIS
1. Turn on voice mode.
2. Wait for “LISTENING.”
3. Say what you want.
4. Wait for JARVIS to think, then answer.

If it’s missing your words, keep things brief, cut background noise, or wear headphones so JARVIS doesn’t pick up its own voice.

💤 Telling JARVIS to stand down
Try saying:
- “Stand down.”
- “Go to sleep.”
- “Stop listening.”
- “That’s all.”
- “Goodbye, JARVIS.”

This just tells JARVIS to stop listening—it doesn’t quit the app.

🫥 Hiding JARVIS
Need the HUD out of sight but want JARVIS running?
Action:                How:
Hide window      Click JARVIS, press ⌘ H
Minimize             Press ⌘ M
Bring back          Click its Dock icon or use ⌘ Tab
Quit                    Press ⌘ Q while JARVIS is active

Heads up: hiding the window doesn’t mute the mic. Say “Stand down” if you want privacy before hiding.

📍 JARVIS in the Menu Bar
- If there’s a JARVIS icon on the right: click it to open the main window.
- No menu bar icon? Not every build includes this—just use ⌘ H to hide and bring it back with the Dock or ⌘ Tab.
- Want it running in the background? Just hide (⌘ H), don’t quit.
- Auto-launch: check System Settings → General → Login Items. JARVIS has to be listed there.

🔔 Updates
When you see an update alert:
1. Open Update Center to check it out, or hit Later to skip.
2. Go to the releases page.
3. Download and install the newest DMG if there’s an update.

Automatic install isn’t there yet. You’ll need to update JARVIS yourself for now.

🛠️ Quick fixes
No mic access?
Go to System Settings → Privacy & Security → Microphone and turn it on for JARVIS.

JARVIS keeps cutting off your speech?
Shorten your sentences and try using headphones. Still happening? Could be a mic or speech detection bug.

No web results?
Check your internet connection first. If that’s fine, make sure you entered a Tavily API key in the dev settings.

Two JARVIS icons in Spotlight?
Delete extra copies from Applications. If the dev build pops up, add its release folder to Spotlight’s Search Privacy.

App won’t open?
Double-check that you downloaded from the official release page. Some builds aren’t signed or notarised yet—macOS will warn you.

👨‍💻 For developers
Source folder: ~/Documents/jarvis-independent-starter

Stack: Electron, React, Vite, Express. AI by Groq, web search by Tavily, native macOS speech output (if using the native build).
To build:
cd ~/Documents/jarvis-independent-starter
npm install
npm run dist

Find build output in the release/ folder. Check package.json before releasing to make sure scripts and version are right.

Secrets: Don’t share your GROQ_API_KEY, TAVILY_API_KEY, or PORT=8787. Never commit real keys, and don’t show them in screenshots.

📦 Official links
- Download JARVIS: https://github.com/bob-the-builder-431/jarvis-independent-releases/releases
- Source: https://github.com/bob-the-builder-431/jarvis-independent-assistant

JARVIS is built to feel more like a helpful assistant—and less like just another chatbot.
