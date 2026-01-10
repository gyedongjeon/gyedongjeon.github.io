---
title: "Projects"
description: "A collection of personal projects exploring AI-native development, full-stack agility, and practical problem-solving."
showTableOfContents: true
---

## Deutschmock
> AI-Driven Practice & Feedback for German Writing Exams

Deutschmock is a full-stack platform designed to help users prepare for German proficiency exams, specifically focusing on the writing (Schreiben) section, through AI-driven feedback.

* **Motivation:** Created to address the lack of instant feedback in self-studying for German writing exams. I built this platform to leverage AI for real-time, high-quality evaluations and strategic score enhancement.
* **Tech Stack:**
    * **Frontend:** Next.js 16 (React 19), Tailwind CSS 4, Radix UI
    * **Backend:** NestJS, PostgreSQL (TypeORM), Passport.js (JWT/OAuth)
    * **AI:** Google Gemini API (Generative AI Integration)
* **Key Strategic Implementations:**
    * **AI Score Enhancement:** Analyzes test patterns and provides actionable feedback specifically designed to improve exam outcomes.
    * **Internationalization & Resource Management:** Supports 40+ languages and features **Usage Quota Management** by implementing authenticated request limits to manage operational costs and ensure fair resource distribution.
* **Methodology: Adopted an AI-augmented engineering workflow to achieve high-velocity development and rapid prototyping across the full stack.
* **Links:**
    * **GitHub:** [View Repository](https://github.com/gyedongjeon/deutschmock)
    * **Website:** [www.deutschmock.com](https://www.deutschmock.com/)


## PartyGame
> A real-time multiplayer gaming platform for seamless social interaction and instant play.

PartyGame is a full-stack web platform designed for seamless, instant multiplayer gaming. It currently features **Imposter**, a social deduction game that challenges players to use real-time communication and strategy to identify hidden imposters hiding among the group.

* **Tech Stack:**
    * **Frontend:** Next.js (React), Tailwind CSS
    * **Backend:** NestJS, WebSockets (Socket.io), PostgreSQL
* **Key Strategic Implementations:**
    * **Real-time Hidden State Management:** Implemented secure server-side logic to handle role assignments, ensuring that sensitive data—such as the identity of the imposters—is masked and only broadcast to authorized clients via WebSockets.
    * **Synchronized Game Lifecycle:** Designed a robust state machine to manage real-time transitions between game phases—lobby, discussion, voting, and results—providing a low-latency experience without the need for manual refreshes.
* **Methodology:** Adopted an AI-augmented engineering workflow to achieve high-velocity development and rapid prototyping across the full stack.
* **Links:**
    * **GitHub:** [View Repository](https://github.com/gyedongjeon/partygame)
    * **Website:** [https://socialpartygame.vercel.app/](https://socialpartygame.vercel.app/)
* **License:** MIT


## Re:Leaf (Chrome Extension)
> A tool to convert scrolling web pages into a paged, e-book-like format for better readability.

* **Motivation:** Developed to improve the reading experience on e-book readers by optimizing web content layout for distraction-free reading.
* **Tech Stack:** JavaScript, CSS
* **Methodology: Adopted an AI-augmented engineering workflow to achieve high-velocity development.
* **Links:**
    * **Chrome Web Store:** [Available here](https://chromewebstore.google.com/detail/releaf/ondpohafbnadicolojjbeecopgionjdo)
    * **GitHub:** [View Repository](https://github.com/gyedongjeon/releaf)
* **License:** MIT
