# Introduction to LaTeX Problem Sheet
Chris Cooling

## Creating a Document
* Create a new Overleaf project called ``Introduction to LaTeX'' - you will complete all exercises before the final exercise in this project
* Delete any sample text already in the project's .tex file
* Create a new article document
* Add a little text to your document
* Add at least one comment
* Compile your document to PDF

## Chapters and Sections

* Add a new chapter to your document (you will need to change the documentclass to ``report'' or ``book'')
* Add a new section to your document
* Add a new subsection to your document


## Modifying Text

* Add some text to your document
* Make part of the text bold
* Make part of the text italic
* Underline part of the text
* Extension: Make some text which is bold, italic, and underlined

## Font Size

* Change the default font size of your document to 12pt
* Change some of the text in your document to a different font size

## Font Typefaces

* Change the default font of your document to ```Helvetica```

## Lists

* Add a bullet-point list to your document
* Add a numbered list to your document
* Extension: Add a nested list to your document


## Mathmode I

* Add an equation to your document
* Embed some mathmode content within some text
* Start both of these pieces of mathmode content with simple content, then make them more complex
* Try to include some maths relevant to your field - research how to include them online if necessary.

## Mathmode II

* Create a block of equations using `alignat`
* Include a 2x2 matrix in one of the equations
* Align the equals sign in each equation

## Cross-Referencing

* Add labels to at least one section and one equation
* Reference the section and equation you just labelled in some text

## Figures

* Add a figure to your document
* Put the figure in the middle of the content you've produced so far
* Change the size of the figure
* Change the vertical position of the figure
* Centre the image horizontally on the page
* Add a caption to the figure
* Extension: Experiment with different vertical placement options to see how it affects the layout of your document


If you receive an error, check the following common issues:


* You should be using the `graphicx' package
* You should have uploaded your image file to Overleaf
* Your file name shouldn't contain spaces
* Your file should be a supported format (no `svg`, `tiff' files)

## Subfigures and Image File Organisation
* Find some pictures you like online (or use some from your research)
* Place them in your project (click upload in the top-left of the Overleaf interface)
* Place the images in a subdirectory called `images`
* Insert a figure containing multiple subfigures in your document, using the images you just uploaded
* Give each subfigure a caption and a label
* Give the figure a label, and a caption
* Reference the figure and a subfigure in some text


## Tables

* Add a table to your document
* Change the text alignment within each column
* Add some horizontal and vertical lines
* Add a caption to the table


## Table of Contents, List of Figures and List of Tables
* Add a table of contents to your document
* Add a list of figures to your document
* Add a list of tables to your document
* Add a short caption to one of your figures or tables, and ensure it appears in the list of figures or tables

## Chemical Formulae

* Add a sentence containing the chemical formula of a compound of your choice
* Add an equation containing the chemical reaction for burning methane: 
  $ \text{CH}_4 + 2\text{O}_2 \rightarrow \text{CO}_2 + 2\text{H}_2\text{O} $
* Extension: Add a skeletal structure diagram of an organic compound of your choice.

## Splitting Your Document

* Add two new .tex files each containing a `chapter` command a short sentence. 
* Use the `include` command to include each new file in your main `.tex` file
* Add the `includeonly` command to your preamble so only one of the chapters is included in the compiled document

## Bibliographies I

* Create a `.bib file` (you can export from a reference manager or create one from scratch)
* Include the bibliography in your .tex file
* Cite some of the bibliography entries in your document


If you receive an error, check the following common issues:


* You should be using the `natbib` package
* You should have uploaded your `.bib` file to Overleaf
* Your `.bib` file should not have a space in its filename
* You should use the `\bibliographystyle` command and selected the `plainnat` style
* You should use the `\bibliography` command. Make sure the name of the `.bib` file you specify is the same as the name of the file you uploaded

## Bibliographies II

* Change something about how the bibliography and citation are formatted
* Add a `\citep` command containing multiple citations
* Add a `\citet` command containing extra details (such as a chapter or page number)
* Manually write a new bibliography entry in your `.bib` file. It should contain:
    * A maths symbol
    * An accented character
    * An acronym

## Hyperlinks

* Use the `hyperref` package to make your references dynamic hyperlinks
* Experiment with different colours for your links and choose one you like

## Acronyms

* Define some acronyms in an `acronym` environment
* Define at least one acronym using `\acrodef`
* Use each acronym at least twice each in some sample text

## Custom Commands

* Create a custom command for a phrase you expect to often in your thesis
* Create a custom command for a mathematical expression. It should take at least one argument.
* Use both custom commands in your document

## Errors

* Make sure you've downloaded this file - the links won't work in the GitHub preview
* Open [this LaTeX project](https://www.overleaf.com/read/gnzphcnqgfvf)
* Make a copy of the project (click the `Menu` button, then `Copy Project``)
* Correct the errors and compile the pdf
* If you get stuck or want to compare your answer, the corrected version can be found [here](https://www.overleaf.com/read/zsmyvxvdcvfr)
