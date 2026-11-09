# Kotoba 言葉

A free, Duolingo-style web app for learning Japanese. No hearts, no ads, no account, no paywall. It is a single HTML file with no dependencies.

**Live app:** add your GitHub Pages link here

## Features

- **Lessons** for Hiragana, Katakana, Kanji and Words. Each lesson introduces new characters, then quizzes you with pick-the-answer and type-it-in-romaji questions. Wrong answers come back until you get them right.
- **Grammar** lessons with short notes and tap-the-words sentence building (topic は, questions with か, objects with を).
- **Kanji** with both On'yomi and Kun'yomi readings.
- **Flashcards** with spaced repetition. Cards you know return after 1, 3, 7, 14, then 30 days.
- **Writing practice** on a drawing pad. Trace over a guide, then hide it and write from memory. Practice lesson by lesson or pick any character.
- **JLPT N5 tab** with exam facts and 25 original practice questions (kanji reading, vocabulary, particles) plus a mixed mock.
- **Voice** using your device's Japanese text-to-speech, with a voice picker and speed setting. Optional speaking practice on words.
- **Profile** with level, XP, streak (it survives one missed day), best streak, progress per script, a 7-day chart and badges.
- **Themes:** Light, Dark or Auto, six colours and a black and white theme.

## How to use

Open `index.html` in a browser, or host it with GitHub Pages:

1. Go to **Settings**, then **Pages**.
2. Choose the **main** branch and the **root** folder, and save.

## Notes and limits

- Progress is saved in your browser (localStorage). It is stored per web address and per browser, so a new link starts fresh.
- The voice depends on the Japanese voice installed on your device. If it is silent, install or re-download Japanese voice data in your phone's text-to-speech settings.
- The speaking check ("Say it") depends on your browser and microphone permission.
- The JLPT questions are original practice written in the style of the N5 test. They are not real exam questions, since the JLPT does not release past exams. Official information is at jlpt.jp.
- The N5 kanji and word coverage is partial.

## Tech

Plain HTML, CSS and JavaScript in one file. The Zen Maru Gothic font loads from Google Fonts, and the app falls back to system fonts if it is offline.

## License

Add a license of your choice if you want others to reuse the code.