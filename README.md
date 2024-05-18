# Supplementary material for “A guide to developing web tools for bioinformatics”

In this document, we present an example application of the "Checklist of important resources for user-friendly web tools".

Below, we present 10 recommendations for producing good web tools. Next, we present a case study of a tool that meets all the requirements, so it can be considered a good example to be followed.


## The Guideline

This guide proposes 10 simple rules for developing a web tool for bioinformatics and producing an article promoting the tool. They are:


> <b>1. Quickstart</b>

The interface should be obvious enough for users to perform a quick analysis. Provide a button on every page that takes users to the page that starts new executions of the tool or that allows them to search and explore data. Use keywords like "new", "explore", "begin", "try", "start", "run", “home", "search", "analysis", and so on.

<b>2. Simple interface</b>

The interface should be simple and clean. It is recommended to use neutral colors (gray, white, black) for most components. Use color contrast to indicate points you want to draw attention to. You can use warm colors (red, yellow, or orange) to draw attention to specific points. Don't include too many visuals that overwhelm users' perception.

<b>3. Explain what this tool is</b>

The interface must indicate the name of the tool (include a logo in the most important region of the page: the top left side) and provide descriptions about it (you can use subtitles, short description texts on the home page and /or include a link to "about" or "help" sections in the main menu).

<b>4. Documentation and tutorials</b>

Provide complete documentation and usage tutorials. This documentation can be added as HTML on a separate page or can be included in PDF or MD format files. Access links should preferably be in the main menu. Video tutorials are welcome. When including functions that allow you to change parameters, include quick ways for the user to learn more about the parameter. You can include contextual help, such as descriptive text next to the field, orhelp buttons that are accessible on demand (when clicked or when the mouse is hovered over the button).

<b>5. Allow exploration</b>

Provide a way for users to explore your data. You can provide a page to explore and filter examples, create an entry example page, provide a simple example in Quickstart, or just put that example in the documentation. 

<b>6. Handle errors</b>

Errors are usually unavoidable. When developing a web tool, you must anticipate possible errors and provide the system with ways to prevent them when possible, or handle them and display personalized messages that explain them. Therefore, conduct tests with the development team and external users without prior knowledge of the tool. Additionally, provide ways for users to get in touch if they encounter any errors. If your tool allows data entry, explain how these files should be formatted.

<b>7. Use visualizations</b>

Use data visualization features such as interactive charts and tables. Remember that visualizations should make data easier to understand and should not be added just because they are pretty. Often, bar or line charts and tables that allow sorting can be the best ways to display results.

<b>8. Export results</b>

After using your tool, users may need or want to export the data (raw data, figures, and tables). Provide ways for this, and explain the available output formats.

<b>9. How to cite this tool</b>

Indicate in the interface how you want users to cite your tool (you can add it in the footer or create a page indicated in the main menu). It is okay to ask users to cite more than one paper (sometimes, you may have published the methodology and the web tool in different papers). However, it is important to use common sense (e.g., do not ask to cite too many articles).

<b>10. Linking article to tool</b>

When writing an article about the tool, it is important to include the access link to the tool in the paper. The access link for the tool paper must be clearly visible in the manuscript (preferably in the abstract). Ensure that the link is available and that there are no broken links in the article. Broken links create a bad first impression.



## Case study

As a case study, we use the PDB (Protein Data Bank) tool as a good example. PDB is available at https://www.rcsb.org/.

Therefore, for each item in the guideline we will present why the PDB web tool meets that requirement.


### Requirement #1. Quickstart

>The interface should be obvious enough for users to perform a quick analysis. Provide a button on every page that takes users to the page that starts new executions of the tool or that allows them to search and explore data. Use keywords like "new", "explore", "begin", "try", "start", "run", “home", "search", "analysis", and so on.

**Does the website meet the requirements?** Yes.

**Why?** The PDB website home page provides menus with recommended keywords.

<img src="data/01.png">

Available at https://www.rcsb.org/. Acessed at May 18, 2024.


### Requirement #2. Simple interface

<code>The interface should be simple and clean. It is recommended to use neutral colors (gray, white, black) for most components. Use color contrast to indicate points you want to draw attention to. You can use warm colors (red, yellow, or orange) to draw attention to specific points. Don't include too many visuals that overwhelm users' perception.</code>
 
<img src="data/02.png">

 
### Requirement #3. Explain what this tool is

<code>The interface must indicate the name of the tool (include a logo in the most important region of the page: the top left side) and provide descriptions about it (you can use subtitles, short description texts on the home page and /or include a link to "about" or "help" sections in the main menu).</code>
 
 
 <img src="data/03.png">
<img src="data/04.png"> 

 
### Requirement #4. Documentation and tutorials

Provide complete documentation and usage tutorials. This documentation can be added as HTML on a separate page or can be included in PDF or MD format files. Access links should preferably be in the main menu. Video tutorials are welcome. When including functions that allow you to change parameters, include quick ways for the user to learn more about the parameter. You can include contextual help, such as descriptive text next to the field, or help buttons that are accessible on demand (when clicked or when the mouse is hovered over the button).
 
<img src="data/05.png"> 
https://pdb101.rcsb.org/learn/guide-to-understanding-pdb-data/introduction 

<img src="data/06.png">

https://www.youtube.com/user/RCSBProteinDataBank 
 
### Requirement #5. Allow exploration
Provide a way for users to explore your data. You can provide a page to explore and filter examples, create an entry example page, provide a simple example in Quickstart, or just put that example in the documentation. 
 
<img src="data/07.png">

 <img src="data/08.png">

### Requirement #6. Handle errors
Errors are usually unavoidable. When developing a web tool, you must anticipate possible errors and provide the system with ways to prevent them when possible, or handle them and display personalized messages that explain them. Therefore, conduct tests with the development team and external users without prior knowledge of the tool. Additionally, provide ways for users to get in touch if they encounter any errors. If your tool allows data entry, explain how these files should be formatted so that errors do not occur.
 
<img src="data/09.png">
 
### 7. Use visualizations

Use data visualization features such as interactive charts and tables. Remember that visualizations should make data easier to understand and should not be added just because they are pretty. Often, bar or line charts and tables that allow sorting can be the best ways to display results.
<img src="data/10.png"> 
https://www.rcsb.org/3d-view/2LZM?preset=validationReport
 <img src="data/11.png">
11 https://www.rcsb.org/sequence/2LZM
 <img src="data/12.png">
12 
https://www.rcsb.org/structure/2LZM

 
### Requirement #8. Export results

After using your tool, users may need or want to export the data (raw data, figures, and tables). Provide ways for this, and explain the available output formats.
 
 <img src="data/13.png">
https://www.rcsb.org/stats/growth/growth-released-structures 

 <img src="data/14.png">

### Requirement #9. How to cite this tool

Indicate in the interface how you want users to cite your tool (you can add it in the footer or create a page indicated in the main menu). It is okay to ask users to cite more than one paper (sometimes, you may have published the methodology and the web tool in different papers). However, it is important to use common sense (e.g., do not ask to cite too many articles).
<img src="data/15.png">
15
<img src="data/16.png"> 
16
 
https://www.rcsb.org/pages/policies#References

 
### Requirement #10. Linking article to tool

The access link for the tool paper must be visible in the manuscript (preferably in the abstract). Ensure that the link is available and that there are no broken links in the article. Broken links create a bad first impression.

H.M. Berman, J. Westbrook, Z. Feng, G. Gilliland, T.N. Bhat, H. Weissig, I.N. Shindyalov, P.E. Bourne, The Protein Data Bank (2000) Nucleic Acids Research 28: 235-242 https://doi.org/10.1093/nar/28.1.235.

<img src="data/17.png">




