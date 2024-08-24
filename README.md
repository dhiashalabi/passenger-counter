# Passenger Counter

This is a simple web application that allows you to count and save the number of passengers entering a station or location. The app is built using HTML, CSS, and JavaScript.

## Features

- **Increment Counter**: Click the "INCREMENT" button to increase the passenger count by one.
- **Save Count**: Click the "SAVE" button to log the current count and reset the counter to zero.
- **Display Previous Entries**: The app displays all saved counts as a record of previous entries.

## Demo

![Passenger Counter Demo](station.jpg)


## Live Demo

You can view a live demo of the Passenger Counter app [here](https://passenger-counter.dhiashalabi.info/).

## Technologies Used

- **HTML**: Structuring the web page content.
- **CSS**: Styling the application, including background image and button designs.
- **JavaScript**: Implementing the logic for counting and saving passenger entries.

## How to Use

1. **Clone the repository** to your local machine.

2. **Open the `index.html` file** in your web browser.

3. **Click "INCREMENT"** to increase the passenger count.

4. **Click "SAVE"** to log the current count. The counter will reset to zero, and the saved count will appear under "Previous entries".

## Code Overview

### HTML

The HTML file sets up the basic structure of the page, including the heading, counter display, buttons, and a section for displaying saved counts.

### CSS

The CSS file is responsible for styling the page, including:

- A background image to enhance the visual appeal.
- Styling the buttons for incrementing and saving the count.

### JavaScript

The JavaScript file contains the core functionality:

- **`increment()`**: Increases the count and updates the display.
- **`save()`**: Saves the current count to the list of previous entries, resets the counter, and updates the display.

## File Structure

- **`index.html`**: Main HTML file.
- **`index.css`**: CSS file for styling.
- **`index.js`**: JavaScript file for functionality.

## Future Enhancements

- Add functionality to remove or edit saved entries.
- Improve the UI/UX with more responsive design and animations.
- Store previous entries in local storage so they persist after page reload.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to explore, modify, and use the code as per your needs. Happy coding!
