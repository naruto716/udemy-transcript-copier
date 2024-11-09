# Udemy Transcript Copier

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A Chrome extension that adds a "Copy Transcript" button to Udemy course pages, allowing users to easily copy the entire course transcript with a single click.

## Features

- Adds a **Copy Transcript** button next to the **Close** button in the transcript sidebar on Udemy course pages.
## Installation

1. **Clone or Download** this repository to your local machine:
   ```bash
   git clone https://github.com/naruto716/udemy-transcript-copier.git
   ```

2. **Open Chrome** and go to the Extensions page:
   ```
   chrome://extensions/
   ```

3. **Enable Developer Mode** in the top-right corner of the page.

4. **Load Unpacked** and select the directory where you cloned or downloaded this repository.

5. The extension should now be installed and appear in your Chrome extensions toolbar.

## Usage

1. Navigate to a course page on [Udemy](https://www.udemy.com/).
2. Open the **Transcript** sidebar by clicking the **Transcript** button.
3. Click the **Copy Transcript** button that appears next to the **Close** button.
4. A success notification will confirm that the transcript has been copied.
5. Paste the copied text wherever you like!

## How It Works

The extension uses a content script (`content.js`) that does the following:

- Detects when the transcript panel is open on Udemy course pages.
- Inserts a **Copy Transcript** button next to the **Close** button in the transcript header.
- When clicked, the button copies all visible transcript text to the clipboard.
- Displays a success message once the transcript is copied.

The extension is styled with custom CSS in `styles.css` to ensure the button integrates smoothly with Udemy’s UI.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
