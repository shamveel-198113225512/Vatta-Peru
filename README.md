# Vatta-Peru

Vatta-Peru

Basic Details
Team Name: BitbyBit
Team Members
Team Lead: [Shamveel P] - [RIT, kottayam]

Member 2: [Febisisna] - [RIT, kottayam]

Project Description
[Our Nickname Generator, "Vatta Peru Co.", is a web-based chatbot that creates quirky, fun, and personalized nicknames. Users can enter their name and a bit about themselves, select a language (English/Manglish, Malayalam, Hindi, or Tamil), and our bot, powered by the Gemini AI, generates five creative and humorous nicknames within a sleek, animated chat interface.]

The Problem (that doesn't exist)
[People are struggling with the unbearable burden of having perfectly normal names. The world is facing a critical shortage of witty, situational, and delightfully absurd nicknames that make friends laugh or cringe. This lack of creativity is a silent crisis we refuse to ignore.]

The Solution (that nobody asked for)
[Our bot provides a vital service by generating outrageously useless nicknames. It leverages the power of Gemini AI to craft witty, culturally relevant, and hilarious names in multiple languages, guaranteeing that you'll question why you wanted one in the first place, but be glad you got it!]

Technical Details
Technologies/Components Used
For Software:

Frontend: HTML5, CSS3, Vanilla JavaScript

Styling: Tailwind CSS for the core layout and utility classes.

AI Model: Google's Gemini AI (gemini-1.5-flash) for nickname generation.

Development Tools: VS Code, Git & GitHub

For Hardware:

[Not Applicable - This is a web-based software project that runs in any modern browser.]

[]

[]

Implementation
For Software: The project is a single-page web application built with HTML, CSS, and JavaScript.

UI & Styling: The user interface is a chat window created with HTML and styled using Tailwind CSS. Custom CSS is added for unique features like the 'Bangers' font for the title, a glowing text effect, animated chat bubbles (jumpIn animation), and a dynamic SVG background.

Client-Side Logic: All interactivity is handled by Vanilla JavaScript.

It manages the state, such as the currently selected language.

It dynamically adds user messages and bot responses to the chat container.

It handles the language selection, updating the UI text and welcome messages from a translations object.

API Integration: On form submission, an async function is triggered.

It constructs a dynamic prompt based on the user's input and the selected language style.

It makes a fetch call to the Google Gemini API endpoint.

The request specifies a JSON response format to ensure the nicknames are returned in a structured way.

While waiting for the API, a "typing" indicator is displayed to the user.

Displaying Results: Once the API returns the list of nicknames, the JavaScript code parses the JSON response and adds each nickname as a separate bot message to the chat, with a staggered animation for a polished effect.

Installation
[```bash
git clone https://github.com/shamveel-198113225512/Vatta-Peru.git

Code snippet


# Run

[Simply open the `index.html` file in any modern web browser. No local server or build process is required.]

---

### Project Documentation

For Software:

 Screenshots1- C:\Users\Administrator\Downloads\Useless project\Vatta-Peru\pic1.png

*Initial view of the 'Vatta Peru Co.' chat interface with the welcome message and language selectors.*

![Screenshot2](C:\Users\Administrator\Downloads\Useless project\Vatta-Peru\pic2.png)
*A user interacting with the bot, showing their input and the bot's "typing" indicator.*

![Screenshot3](C:\Users\Administrator\Downloads\Useless project\Vatta-Peru\pic3.png)
*The final AI-generated nicknames are displayed in animated chat bubbles after the bot processes the request.*

# Diagrams

![Workflow](https://i.imgur.com/uQW5Tf9.png)
*Basic application workflow: The user interacts with the UI, which triggers JavaScript to call the Gemini API. The response is then processed and displayed back in the UI.*


---

### Project Demo

# Video

[https://www.youtube.com/watch?v=dQw4w9WgXcQ]
*The demo video shows the full user journey: launching the page, selecting a different language (Tamil), entering a name and description, and receiving the five AI-generated nicknames with all the UI animations and effects.*

# Additional Demos

[N/A]

---

## Team Contributions

-   **Shamveel P**: Lead Frontend Development (HTML, JavaScript), API Integration with Gemini, UI/UX Design, and implementation of CSS animations.
-   **Febisisna**: Prompt Engineering for the AI model, creating and managing the multi-language translation strings, and project documentation.
