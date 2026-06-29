# Leet2Git

I wanted an easy way to automatically push my accepted LeetCode solutions to GitHub. The existing options required manually pushing every solution, and the Chrome extensions I tried were either unreliable or no longer working.

Instead of settling for that, I built my own solution using **AntiGravity**.

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
