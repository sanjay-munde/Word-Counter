# Word Counter

Word Counter is a web application built in HTML, CSS, and JavaScript that allows users to analyze text input by providing various statistics such as character count, word count, sentence count, paragraph count, reading time, and readability score. Additionally, it generates a list of the top keywords present in the input text.

## Features

- **Character Count:** Counts the number of characters entered in the textarea.
- **Word Count:** Counts the number of words entered in the textarea.
- **Sentence Count:** Counts the number of sentences entered in the textarea.
- **Paragraph Count:** Counts the number of paragraphs entered in the textarea.
- **Reading Time:** Estimates the reading time based on the average reading speed (275 words per minute).
- **Top Keywords:** Identifies and displays the top 4 keywords entered in the textarea.
- **Readability Score:** Fetches the readability score using an external API and displays it in a human-readable format.

## Usage

1. Enter text into the provided textarea.
2. The application will dynamically update the statistics and display them below the textarea.
3. Click on the "Show readability score." link to fetch and display the readability score.

## External API

The application uses the "readability-metrics" API from Mashape to fetch the readability score.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/sanjay-munde/Word-Counter/edit/main/LICENSE) file for details.
