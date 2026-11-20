JAMB 2027 STUDY HUB — COMBINED HTML + AI PACKAGE

MAIN WEBSITE
- index.html is the combined website based on the current uploaded index12.html.
- The optional Textbook Library and JAMB 2027 Self-Teaching Notes sections have been added.
- The vocabulary bank is expanded from 253 to 282 words.
- Chemistry and Physics self-teaching PDF notes and all four Exam Focus books are included.
- The current website's existing lesson sequence, topic tests, progress tracking, and subject structure are retained.

OPEN AS A STATIC WEBSITE
- Open index.html in a modern browser, or upload index.html, books/, and notes/ to the same website root.
- Textbook and self-teaching PDF links rely on the books/ and notes/ folders being kept beside index.html.
- The AI Tutor and AI-generated topic packs require the backend; they will not work from a file:// page or static-only hosting.

RUN WITH THE AI BACKEND
1. Install Node.js 20 or newer.
2. In this folder run: npm install
3. Set OPENAI_API_KEY as a server environment variable in your hosting dashboard or terminal.
4. Optional: set OPENAI_MODEL to a model available to your API project. The server default is gpt-6-astra; change it if that model is not enabled for your API account.
5. Run: npm start
6. Open the local server URL (normally http://localhost:3000).

SECURITY AND COST
- Never put your API key in index.html or share it with students.
- AI requests are sent to the configured backend and may incur API charges.
- AI-generated questions are original practice questions, not authentic JAMB past questions.
- Browser progress is stored locally and is not automatically synchronised across devices.

FILES
- index.html: standalone front page for static hosting
- public/index.html: same page served by the Node backend
- books/: Exam Focus reference PDFs
- notes/: Chemistry Edition 3 Corrected and Physics Edition 1 self-teaching notes
- server.js / package.json: secure AI backend
