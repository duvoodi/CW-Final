
# Computer Workshop Final Assignment

  

## 📖 Overview

This repository contains the final assignment for my computer workshop course. The assignment involves writing answers to a set of questions using LaTeX and automating the process of converting them into a PDF using GitHub Actions.

  

## 🎯 Purpose

The primary objectives of this repository are:

- To document and submit the final assignment using LaTeX.

- To automate the PDF generation process whenever a new tag and release are created.

- To demonstrate the use of GitHub Actions for continuous integration.

  

## 📂 Repository Structure

The repository consists of the following key components:

-  **`/`** – Contains the LaTeX source file for the assignment and this readme.

-  **`/img/`** – Contains the image assets used for LaTeX source file.

-  **`/.github/workflows/`** – Contains the GitHub Actions workflow for automating the PDF

-  **`Releases`** – Stores the generated PDF files.

  

## ⚙️ Workflow

The workflow for generating the assignment PDF is as follows:

1. Write answers in LaTeX within the `/` directory.

2. Commit and push the changes to the repository.

3. Create a new tag and release to trigger the GitHub Actions workflow.

4. GitHub Actions compiles the LaTeX files into a PDF.

5. The generated PDF is automatically uploaded to the release section.

  

## 🚀 How to Use

Follow these steps to use the repository:

1. Clone the repository:

```bash

git clone https://github.com/yourusername/computer-workshop-final.git

cd computer-workshop-final

```

2. Modify the LaTeX files in the `/` directory.

3. Commit the changes and push them to GitHub.

```bash

git commit -am "Updated answers"

git push origin main

```

4. Create a new tag and release on GitHub to trigger the PDF build process.

  

**🛠 Tools Used**

The following tools were used to set up this repository locally:

-  **Git** – For version control and managing repository changes.

-  **LaTeX** – To write and format the assignment.

-  **MiKTeX** – A LaTeX distribution used for compiling documents.

-  **VS Code** – The code editor used for writing and managing LaTeX files.

  

## 📄 License

This project is for educational purposes only and is not intended for commercial use.

  

## ✨ Acknowledgements

Special thanks to Mr. Milad Zarei, for his excellent teaching and guidance throughout the computer workshop.