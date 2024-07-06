# Fake Hacking Interface

A fun and interactive fake hacking interface built with HTML, CSS, and JavaScript. Users can input the number of hacks and hacking details to simulate a hacking process on the console.

## Features

- Dynamic fake hacking sequence based on user input.
- Animated typing effect to simulate real-time hacking.
- Blinking cursor animation for a realistic console look.
- User-friendly form for specifying the number of hacks and details.

## Demo

![Fake Hacking Interface Demo](demo.gif)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Fake-Hacking-Using-HTML-CSS-JS.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Fake-Hacking-Using-HTML-CSS-JS
    ```
3. Open `index.html` in your preferred web browser.

## Usage

1. Open `index.html` in a web browser.
2. Fill in the number of hacks and hacking details in the form.
3. Click the "Start Hacking" button to begin the fake hacking simulation.
4. Watch the console display the simulated hacking sequence based on your input.

## Project Structure

- `index.html`: The main HTML file that contains the structure of the interface.
- `styles.css`: The CSS file that styles the interface.
- `script.js`: The JavaScript file that handles the logic for the fake hacking simulation.

## Customization

To customize the fake hacking commands, you can edit the `defaultCommands` array in `script.js`:

```javascript
const defaultCommands = [
    'Connecting to Mobile...',
    'Connection established.',
    'Loading Whatsapp...',
    'Opening passwords...',
    'Accessing mainframe...',
    'Downloading data...',
    'Trace detected! Initiating countermeasures...',
    'Transfer complete.',
    'Whatsapp Hacked in 1 Hour...',
    'continueee...'
];
