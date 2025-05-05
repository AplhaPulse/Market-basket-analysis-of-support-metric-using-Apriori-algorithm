# Finding Popular Item Combinations in Purchases

This project uses computer code on colab to find out which items are often bought together in shopping trips.

## Purpose

 Shows how to find groups of items that are often bought together in shopping data.
 Explains how we measure how often items appear together (using a number).
 Gives you the basics for understanding how to find these connections in shopping data.
 Uses pictures to help see the popular items and how common they are.

## Implementation
Uses Python and special tools to work with data.
Uses a computer method to find groups of items that appear often.
Counts how often single items and groups of items are bought (this is the "support").
Finds the groups of items that are bought together more often than a set amount.
Makes different kinds of pictures to show the results.

## Usage

1.  Get the needed computer tools:
    ```bash
    pip install pandas mlxtend wordcloud matplotlib seaborn squarify google-colab
    ```
2.  Give it your shopping data: The code will ask you to upload a file (like an Excel sheet) that has your shopping trip information. One of the columns should list the items bought in each trip.
3.  Run the computer code: Open and run the Python code. It will:
     Read your shopping data.
     Get it ready for analysis.
     Find the popular item combinations for different levels of "how often."
     Show you lists of these popular combinations.
     Create and show you different kinds of pictures.
4.  Look at the results:
    Lists of popular items:The code will show you lists of items that are often bought together.
    Visualisations:The following sections explain the different kinds of pictures you'll see.

## Key Concepts
Finding Item Combinations: A way to see which products customers buy at the same time.
Support: A number that tells us how often an item or a group of items is bought.
Popular Item Combination: A group of items that is bought together more often than we expect.
Shopping Data: Information about what was bought in each shopping trip.

## Output

The code will show you:

 Lists of popular item combinations for different levels of how often they appear.
 Different kinds of pictures of the popular items.

##Visualizations

### Word Cloud
 A picture where words that appear more often are bigger. In this project, bigger item names mean those items appear more often in popular combinations.

### Heatmap

A colored chart that shows how often pairs of items or groups of items are bought together. Darker colors mean they are bought together more often.

### Treemap

A chart that uses blocks to show how common different groups of items are. Bigger blocks mean those groups are more common in the shopping data.

## Information about the parameters used
How often items need to be bought together: The code tries different levels of "how often" (from 0.01 to 0.09). You can change these numbers in the code.
How the pictures look: You can change the colors, sizes, and other looks of the pictures in the code.

