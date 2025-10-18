# Basic Bond Concepts and the Term Structure of Interest Rates

**This Jupyter Book is Chapter One of the Volume *Basic Concepts of Fixed Income***.

**Highlights of the Chapter are:**

* ***Financial Concepts***

    * *Basic bond pricing*
    * *Defining the term structure of interest rates*
    * *Calculating and graphing the term structure of interest rates*
    * *The term structure and the state of financial markets*

* ***Python Concepts***

    * *NumPy arrays*
    * *Python DataFrames*
    * *Accesing data with a URL address*
    * *Custom modules*

## Background


<div style="font-family: 'Garamond', serif;
    font-size: 16px;
    text-indent: 0.25in;
    line-height: 1.5;">

This chapter uses the Python libraries Pandas and NumPy. The basic usage of these libraries is detailed in two Notebooks: "[A Quick Introduction to Pandas](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_Pandas.html)" reviews some basic concepts of Pandas, and "[A Quick Introduction to NumPy](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_NumPy.html)" does the same for NumPy. These Notebooks are part of the introductory volume [Background Material: An Introduction to Python for Financial Python](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/intro.html). Portions of the volume will be cited throughout this chapter. Feel free to consult these materials as needed for greater discussion of Python concepts.
</div>
</br>

## Chapter One: A Road Map

<span style="font-family: 'Garamond', serif;
    font-size: 16px;
    text-indent: 0.25in;
    line-height: 1.5;">

**1. Python for Bonds and Interest Rates**

**2. Introduction to Bond Pricing**


 **5. Creating a Pandas DataFrame from NumPy Arrays**


 **7. Calculating the Term Structure with Treasury Bills**


 **8. Return to the Calculations**


 **9. Graphing the Term Structure**


 **11. Graphing the Term Structure (Again)**

 **12. Python, Pandas, NumPy, and Financial Insights**

 **Chapter Exercise: Calculating and Plotting Spot and Forward Rates**
</span>


**The Chapter includes five sections.**

1. *Introduction to Bond Pricing* covers some  basic concepts. 
2. The  Jupyter notebook *NumPy and Pandas* intrduces and illustrates the modules. 
3. The  Jupyter notebook *Calculating And Graphing The Term Structure Of Interest Rates* uses NumPy and Pandas to:
   * download data from DropBox that is used to calculate and graph the term structure on September 15$^{th}$ 2022.
   * download data from the U.S. Treasury that is used to calculate and graph the term structure on September 30$^{th}$ 2025
4. *Python, Pandas, NumPy, and Financial Insights* summarizes the financial concepts and results.
5. *Functions Imported By Basic Concepts Of Fixed Income* descries the functions imported from DropBox (*module_basic_concepts_fixed_income*)..


**Interacting with Jupyter Notebooks**

The Jupyter notebooks can be viewed just as you are viewing this page; however, they offer deeper interactive capabilities.  For example the upper-right corner of *Calculating And Graphing The Term Structure Of Interest Rates* shows icons for launching and downloading the notebook.  Downloading needs no elaboration.  The launch icon offers three options:

* **Binder:**
    * Launches in a new browser tab, typically within a minute. 
    * Supports up to one hundred simultaneous users.
    * Functions like any other Jupyter notebook, but runs remotely.
    * Allows you to:
        * Execute existing cells.
        * Add or modify cells.
        * Download the notebook.
    * Note: In this mode the notebook will not be available if saved. 

* **Colab:**
    * Offers the quickest and easiest access without requiring Binder.
        * A Google Drive is not necessary for launching.
        * You can download the notebook without signing into a Google account.
    * Note: You must sign in to a Google account to execute cells or make a copy.
      

* **Live Code:**
    * Requires a Binder launch and is ideal for demonstrations.
    * Enables you to:
        * Run code in existing cells.
        * Alter code in existing cells.
    * Note: You cannot add cells or save results in this mode.

**Any code cell in a notebook or code block in a text cell can be copied to the clipboard by moving your cursor to upper-right corner of the code cell or code block.**


```{tableofcontents}
```
