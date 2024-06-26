## Movie Search GUI

This Java application provides a user-friendly graphical interface for searching movie information using the OMDb API. Users can input the name of a movie or web series, and the application retrieves detailed information about the title, including its release year, runtime, genre, plot, ratings, and more.

### Features:

- **Simple Interface**: The graphical user interface (GUI) allows users to easily input movie names and view detailed information.
- **Search Functionality**: Users can search for movie information by entering the name of the movie or web series.
- **Clear Functionality**: Allows users to clear the search field and reset the display area.
- **Error Handling**: Provides feedback for errors such as offline status or when the requested movie is not found.
- **Loading Indicator**: Displays a progress bar to indicate when the application is retrieving movie information.

### Technologies Used:

- **Java Swing**: Used for building the graphical user interface.
- **OMDb API**: Integrated to fetch movie information.
- **HTTPURLConnection**: Utilized for making HTTP requests to the OMDb API.
- **JSON Parsing**: Parses the JSON response from the API to extract relevant movie details.

### Usage:

1. Enter the name of the movie or web series in the input field.
2. Click the "Search" button to retrieve information.
3. The details of the movie will be displayed in the result area.
4. If no movie is found or there is an error, an appropriate message will be shown.

### How to Run:

1. Clone this repository to your local machine.
2. Ensure you have Java installed.
3. Compile the `MainGUI.java` file.
4. Run the compiled Java class file (`MainGUI.class`).

### Contributions:

Contributions are welcome! If you have any ideas for improvements or find any issues, feel free to open an issue or create a pull request.

### License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Stone Paper Scissors Game With GUI

This Java application provides a graphical user interface (GUI) for playing the classic game of Stone Paper Scissors against the computer. Users can choose their move (stone, paper, or scissors) by clicking on the corresponding buttons, and the computer's move is randomly generated. The result of the game (win, lose, or tie) is displayed in the result label.

### Features:

- **Interactive Interface**: Simple and intuitive GUI allows users to select their move with a click of a button.
- **Randomized Computer Move**: The computer's move is randomly generated, ensuring unpredictability.
- **Result Display**: The result label dynamically updates to show the outcome of the game (win, lose, or tie).
- **Responsive Design**: The GUI is designed to adapt to different screen sizes and resolutions.

### Technologies Used:

- **Java Swing**: Utilized for building the graphical user interface.
- **Random Number Generation**: Randomly selects the computer's move using Java's `Random` class.
- **Action Listeners**: Implemented to handle button clicks and initiate game rounds.
- **Conditional Statements**: Used to determine the winner based on the user's and computer's moves.

### Usage:

1. Click on one of the buttons ("Stone", "Paper", or "Scissors") to select your move.
2. The computer's move will be randomly generated.
3. The result of the game (win, lose, or tie) will be displayed in the result label.

### How to Run:

1. Clone this repository to your local machine.
2. Ensure you have Java installed.
3. Compile the `StonePaperScissorsGUI.java` file.
4. Run the compiled Java class file (`StonePaperScissorsGUI.class`).

### Contributions:

Contributions are welcome! If you have any ideas for improvements or find any issues, feel free to open an issue or create a pull request.

### License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
