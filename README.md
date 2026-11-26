# ISTQB CTFL – procvičování (Czech exam trainer)

A web app for practising the official ISTQB® Certified Tester Foundation Level (CTFL v4.0) sample exams in Czech. It contains every question from sample exams A, B, C and D, with the correct answers and explanations from the official answer sheets. Questions move from "Neumím" (don't know) to "Umím" (know) only after three correct answers in a row.

**▶ Try it online:** https://sonkuc.github.io/ISTQB-CZ-excercise/ *(available once GitHub Pages is enabled)*

> The app's user interface and all questions are in Czech, the language of the exam.

## Features

- **186 questions:** sample exam A (40 questions plus 26 additional ones from its appendix), and B, C and D (40 questions each).
- **Verified answer key:** each answer was checked against three sources in the official PDFs: the answer key table, the detailed answer row, and the "Je správně" (correct) lines in the explanation.
- **Single and multiple answers:** questions that need two answers say so ("Vyberte DVĚ odpovědi").
- **Colour feedback:** green = correct, red = wrong, orange = partly correct.
- **Corrections:** after a mistake you can change your choice and try again, but the correction does not count towards your streak.
- **Three in a row:** a question moves to *Umím* after three consecutive correct first attempts. A wrong answer in *Umím* moves it back to *Neumím* automatically, and you can also move it back by hand.
- **Random order:** questions come in random order from the category you are in, with no repeats until all of them have been shown.
- **Filters:** by sample exam (A–D) and by syllabus chapter or sub-chapter, in any combination.
- **Explanations:** the official explanation appears when you click *Proč?* (Why?).
- **Tables and diagrams:** questions with tables, state diagrams and charts are shown as images cut from the original PDF, so nothing gets distorted.
- **Progress overview** per syllabus chapter.
- **Light and dark mode**, with a responsive layout for desktop and mobile.
- **Keyboard shortcuts:** A–E selects an answer, Enter evaluates or moves to the next question, P shows the explanation.

## Getting started

- **Online:** open the link above. On a phone, use your browser's "Add to Home Screen" option to use it like an app.
- **Offline:** download `index.html` and open it in any modern browser. No installation is needed.

## Data storage and privacy

Progress is stored **only in your browser** (localStorage) and is never sent to a server. To move progress to another device, use **Postup → Zálohovat / Obnovit** (Progress → Back up / Restore).

## Tech stack

A single `index.html` file: HTML, CSS and vanilla JavaScript, with no frameworks, build step or backend.

## Source and copyright

The questions, answers and explanations come from the official ISTQB® CTFL v4.0 sample exams in Czech translation (sample exam A v1.7.1, B v1.7.1, C v1.6, D v1.5) and are © International Software Testing Qualifications Board (ISTQB®). ISTQB® is a registered trademark of ISTQB. They are used here for non-commercial study purposes, with the source acknowledged as the sample exams' copyright notice requires.

The app code is released under the [MIT](LICENSE) licence.
