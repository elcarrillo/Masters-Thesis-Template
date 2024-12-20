# Master's Thesis Template

This repository offers a <img src="https://upload.wikimedia.org/wikipedia/commons/9/92/LaTeX_logo.svg" alt="LaTeX Logo" title="LaTeX Logo" style="background-color:white; padding:5px; width:50px; height:auto;"> template created by **Edgar Carrillo**, originally designed to meet the thesis formatting requirements for Fisk University's MS in Physics program. 

To assist others in understanding and crafting a well-structured master's thesis, I have made this template publicly available as an example of a complete thesis framework.

<img src="./body/images/books.jpg" alt="Books Image" title="This is a books image" width="500">



## Directory Structure
- `body/`: Contains all core components of the thesis.
  - `images/`: Folder for storing images used in the thesis.
  - `abstract.tex`: Contains the abstract section.
  - `acknowledgment.tex`: Contains the acknowledgment section.
  - `appendix.tex`: Contains the appendix.
  - `chapter1_intro.tex`: The introduction chapter.
  - `chapter2_methods.tex`: The methods chapter.
  - `chapter3_results.tex`: The results chapter.
  - `chapter4_discussion.tex`: The discussion chapter.
  - `chapter5_conclusion.tex`: The conclusion chapter.

- `approval_sheet.tex`: Contains the approval sheet template.
- `bibliography.bib`: Bibliography file for managing references.
- `main.tex`: The main LaTeX file to compile the thesis.
- `preamble.tex`: Contains preamble settings such as packages, formatting, and custom definitions.
- `title_page.tex`: Contains the title page template.

## Key Features
- Modular Structure: Each section and chapter is in a separate `.tex` file for easy organization and editing.
- Image Management: Images are stored in the `body/images/` folder, allowing for centralized asset management.
- Standardized Formatting: The `preamble.tex` ensures compliance with Fisk University's formatting requirements.
- Custom Margins: Page margins are defined using the `geometry` package in `main.tex`. (Values are based on Fisk University requirements)

## Usage Instructions
1. Edit Content: Modify the content in the relevant `.tex` files in the `body/` directory.
2. Add Images: Place images in the `body/images/` folder and reference them in your chapters.
3. Compile: Compile `main.tex` using your preferred LaTeX editor (e.g., Overleaf, TeXShop, or VS Code with LaTeX Workshop).
4. Bibliography: Manage citations using the `bibliography.bib` file.

## Notes
- Ensure the title page, approval sheet, and margins comply with any specific updates to university formatting guidelines.
- Use `preamble.tex` to customize additional packages or macros as needed.

## Acknowledgment
This template includes placeholder text generated with the assistance of ChatGPT, an AI language model developed by OpenAI. The dummy text and its structure were used as a framework to streamline the development of this LaTeX template.


---

For questions or assistance, feel free to contact Edgar Carrillo (mailto:elcar@uoregon.edu).
