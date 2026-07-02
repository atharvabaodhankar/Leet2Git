# Leet2Git

I wanted an easy way to automatically push my accepted LeetCode solutions to GitHub. The existing options required manually pushing every solution, and the Chrome extensions I tried were either unreliable or no longer working.

Instead of settling for that, I built my own solution .

### Features

* 🚀 Automatically pushes every accepted LeetCode solution to a GitHub repository.
* 📊 Displays the total number of solved problems.
* 🟢🟡🔴 Shows separate counts for Easy, Medium, and Hard problems.
* 📝 Lists your recently submitted solutions.
* 📂 Organizes each solution using the format:

  ```
  (LeetCode Number)_(Problem Name).<extension>
  ```

  Example:

  ```
  15_3Sum.py
  42_Trapping_Rain_Water.cpp
  1_Two_Sum.java
  ```
* ⚙️ During the initial setup, you only need to provide:

  * Your GitHub **Personal Access Token (PAT)**
  * Your GitHub username
  * The name of the repository where you want your solutions to be stored
* 🔄 Once configured, every accepted LeetCode submission is automatically pushed to the specified GitHub repository—no manual uploads required.

This extension keeps your GitHub repository up to date with your LeetCode journey, making it effortless to maintain a well-organized coding portfolio.

## Installation (Developer Mode)

1. Clone or download this repository:

   ```bash
   git clone https://github.com/NANDU-SK-004/Leet2Git.git
   ```

   Alternatively, click **Code → Download ZIP** on GitHub and extract it.

2. Open Google Chrome and navigate to:

   ```
   chrome://extensions/
   ```

3. Enable **Developer mode** using the toggle in the top-right corner.

4. Click **Load unpacked**.

5. Select the cloned (or extracted) **Leet2Git** project folder. Make sure you select the folder containing `manifest.json`.

6. The extension will now appear in your extensions list. You can optionally pin it from the Extensions menu.

7. Open the extension popup and complete the one-time setup by entering:

   * GitHub Personal Access Token (PAT)
   * GitHub Username
   * Repository Name

8. Open LeetCode and start solving problems. Every **Accepted** submission will be automatically pushed to your configured GitHub repository.

> **Note:** The `README.md` file is part of the repository and does not affect the extension. Chrome only cares that the selected folder contains a valid `manifest.json` file.

