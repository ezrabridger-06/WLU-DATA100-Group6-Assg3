# GROUP NOTE
- For any lines with `# YOUR CODE HERE` in the Rmd file, please remove them when adding your code. Keep all other comments unless otherwise noted as well
- Remember to not copy and paste the entire file on your side, as it might mess with the setup done here. Just copy the objects (`object_a <- ...`) that you did
- When adding your code/editing the file, select the respective branch (e.g. Pt-1-Data-set-1) from the branch list on the top left
    + Pt-1-General and Pt-2-General are for non-R code or misc changes to the files
    + After adding/editing, press _Commit changes_ on the top right, keep the _Commit message_ short (use _Extended description_ if needed) and leave the _Commit directly to the `<name>` branch selected_
- If you write the parquet and have the file on your computer, upload it to the Assignment Sources folder in that branch
- If you are stuck or need help in the middle of your code:
    + Edit and commit as above then on the branch page
    + Click on _Compare and pull request_ on the yellow banner on top
    + Add details and click _Create pull request_ so we can go in to discuss and still be able to further edit that part


_(Extracted from the template Rmd files)_
# PART 1

This file will be submitted as an Rmd file to GradeScope. You will need to create a group on GradeScope with the correct members. *If the person who submits this does not list you, you will not get a grade on this assignment!!!* Make sure you trust the person who is submitting it!

## Overview

This is **Part 1** of the group assignment, in which you'll demonstrate your ability to clean the data sets.

In this part, you will prepare the following data sets for analysis in Part 2. Note that you'll only need to use three of them, so you can focus on those three for cleaning and get started on Part 2.

Once you've completed the relevant sections, you will have the following files in your working directory:

1. `cyclones_data.parquet` contains data for hurricane strength in both the Atlantic and North Pacific basins.
2. `ice_extent_yearly.parquet` contains the yearly ice extent for the Arctic and the Antarctic poles.
3. `climate_awareness.parquet` contains the proportion of people from each country who answered "no", "a little", ... to a question asking about their awareness of the actual definitions of climate change.
4. `covid_2020.parquet` contains the total reported cases of COVID-19 in the year 2020 for all countries.
    - It also, quite helpfully, includes the continent on which each country sits, which can be joined with other data frames (with some care).
5. `happiness.parquet` contains information about the happiness of countries in the world, as measured by the `life_ladder` question (among other survey responses).



# PART 2

## Important

You **must** be in a group in MyLS in order to see the DropBox used for submission. Even if you're alone, you must join a group by yourself.

You **must** be in a group with people from the same section as you. MyLS does not allow for groups including students from both Data100A and Data100B.

## Instructions

You are encouraged to remove this instruction section prior to submission.

It is recommended that you follow the structure of this template. The text is all placeholder - you are free to change any/all wording as you please, but it is very helpful for the grading process if you keep the same structure. Anything in <<double angle brackets>> definitely needs to be changed, but you are free to change any/all sentences!

Note that all of the code is *hidden* by default. This file will be graded based on the insights, not the code.

You will only submit the PDF version of this document. To knit to PDF, you'll need to run `install.packages("tinytex")` in the console, followed by `tinytex::install_tinytex()` (DO NOT PUT THESE COMMANDS IN AN RMD FILE!!!). If you encounter errors in "Knit to PDF", you can "knit to html" and then print the html file to PDF using your operating system's PDF view (e.g. Adobe Acrobat). Only standalone PDF files will be accepted by MyLS.

## References

I am not strict about MLA or APA style or anything like that. For this report, I would much rather have your citations be easy to match to your insights.

The easiest way is to use Rmd's `[footnote](https://bookdown.org/yihui/rmarkdown/markdown-syntax.html#inline-formatting)` syntax. This will put a number beside the word where the footnote appears, and the full text of the footnote at the bottom of the page (pdf) or end of the document (html). The syntax is: ^[See the source view to see this footnote], where I suggest that you put in something like this ^[The relevance to the insight is ... . From <<name of source and name of article>>, published on <<date>>, url: <<link to page>>] to make references for this assignment.

Alternatively, you could make a list of citations with their main arguments and why they're relevent to your insights, methods, etc.

The link above also references "bibtex" files. These are also extremely convenient, but have a steep learning curve and they make it difficult to tie them to an insight. If you use bibtext, then make sure that you provide a sentence to describe the source and it's relevance when you cite it - don't just add citations to the end of a sentence (this is common practice in academia, but I want to know that your citations are directly relevant for this assignment).
