# Quiz CLI

An interactive command-line quiz game for learning JavaScript, Node.js, and general programming concepts.

## Features

- Choose from JavaScript Basics, Node.js Fundamentals, and General Programming categories.
- Select all available questions or a shorter three- or five-question quiz when available.
- Questions are shuffled for each quiz.
- Receive immediate correctness feedback and explanations.
- Review incorrect answers and see a final score and performance message.
- Uses ANSI terminal colors without external runtime dependencies.

## Requirements

- Node.js 18 or newer
- A terminal that supports standard ANSI color escape sequences

## Installation

Clone the repository and move into the application directory:

```bash
git clone https://github.com/Jorge-gonmae/test-app.git
cd test-app/test-app
```

No package installation is required because the application uses Node.js built-in modules only.

## Usage

Start the quiz with:

```bash
npm start
```

Follow the prompts to choose a category, select the number of questions, answer each question, and optionally play again.

## Project Structure

```text
test-app/
├── data/questions.json  # Quiz categories and questions
├── index.js              # Application entry point and game loop
├── package.json          # Project metadata and npm scripts
└── src/
    ├── colors.js         # ANSI color helpers
    ├── input.js          # Readline prompts and selections
    └── quiz.js           # Quiz state, scoring, and results
```

## Testing

Run the configured Node.js test command with:

```bash
npm test
```

## License

This project is licensed under the MIT License.
