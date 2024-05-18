# Supplementary material for “A guide to developing web tools for bioinformatics”

In this document, we present an example application of the "Checklist of important resources for user-friendly web tools".

## The Guideline

This guide proposes 10 simple rules for developing a web tool for bioinformatics and producing an article promoting the tool. They are:


<b>1. Quickstart</b>

The interface should be obvious enough for users to perform a quick analysis. Provide a button on every page that takes users to the page that starts new executions of the tool or that allows them to search and explore data. Use keywords like "new", "explore", "begin", "try", "start", "run", “home", "search", "analysis", and so on.

2. Simple interface

The interface should be simple and clean. It is recommended to use neutral colors (gray, white, black) for most components. Use color contrast to indicate points you want to draw attention to. You can use warm colors (red, yellow, or orange) to draw attention to specific points. Don't include too many visuals that overwhelm users' perception.

3. Explain what this tool is

The interface must indicate the name of the tool (include a logo in the most important region of the page: the top left side) and provide descriptions about it (you can use subtitles, short description texts on the home page and /or include a link to "about" or "help" sections in the main menu).

4. Documentation and tutorials

Provide complete documentation and usage tutorials. This documentation can be added as HTML on a separate page or can be included in PDF or MD format files. Access links should preferably be in the main menu. Video tutorials are welcome. When including functions that allow you to change parameters, include quick ways for the user to learn more about the parameter. You can include contextual help, such as descriptive text next to the field, orhelp buttons that are accessible on demand (when clicked or when the mouse is hovered over the button).

5. Allow exploration

Provide a way for users to explore your data. You can provide a page to explore and filter examples, create an entry example page, provide a simple example in Quickstart, or just put that example in the documentation. 

6. Handle errors

Errors are usually unavoidable. When developing a web tool, you must anticipate possible errors and provide the system with ways to prevent them when possible, or handle them and display personalized messages that explain them. Therefore, conduct tests with the development team and external users without prior knowledge of the tool. Additionally, provide ways for users to get in touch if they encounter any errors. If your tool allows data entry, explain how these files should be formatted so that errors do not occur.

7. Use visualizations

Use data visualization features such as interactive charts and tables. Remember that visualizations should make data easier to understand and should not be added just because they are pretty. Often, bar or line charts and tables that allow sorting can be the best ways to display results.

8. Export results

After using your tool, users may need or want to export the data (raw data, figures, and tables). Provide ways for this, and explain the available output formats.

9. How to cite this tool

Indicate in the interface how you want users to cite your tool (you can add it in the footer or create a page indicated in the main menu). It is okay to ask users to cite more than one paper (sometimes, you may have published the methodology and the web tool in different papers). However, it is important to use common sense (e.g., do not ask to cite too many articles).

10. Linking article to tool

The access link for the tool paper must be visible in the manuscript (preferably in the abstract). Ensure that the link is available and that there are no broken links in the article. Broken links create a bad first impression.

## Case study

As a case study, we use the PDB (Protein Data Bank) tool as a good example. PDB is available at https://www.rcsb.org/.

Therefore, for each item in the guideline we will present why the PDB web tool meets that requirement.

### Requirement #1. Quickstart

<code>The interface should be obvious enough for users to perform a quick analysis. Provide a button on every page that takes users to the page that starts new executions of the tool or that allows them to search and explore data. Use keywords like "new", "explore", "begin", "try", "start", "run", “home", "search", "analysis", and so on.</code>


<img src="data/01.png">
