# FAU Introduction to Data Science - guest talk

Presentation given to [Dr. Marques'](https://www.ogemarques.com/) Introduction to Data Science class - Fall 2020

**Answering Questions with Data, bridging the gap between technical analysis and stakeholders point-of-view with Jupyter notebooks** 

* How to write well-structured, understandable, reliable, flexible Jupyter notebooks
* How to present the results of our investigations to the people who asked the questions, the stakeholders

In the first part we take a Jupyter notebook that produces the right result, but lacks good structure and proper coding practices, and transform it to a good notebook.

What is a _good_ notebook?

* Overall organization is logical
* Important assumptions and decisions are spelled out
* Code is easy to understand
* Code is flexible (easy to modify)
* Code is resilient (hard to break)

We transform it in a sequence of steps. Each step addresses a set of related items.

- [Step 1](salary-discrimination-by-gender-step-1.ipynb): the original notebook, the one that lacks structure and proper coding practices.
- [Step 2](salary-discrimination-by-gender-step-2.ipynb): adds a description, organize into sections, add exploratory data analysis.
- [Step 3](salary-discrimination-by-gender-step-3.ipynb): make data clean-up more explicit, explain why certain numbers were chosen (the assumptions behind them).
- [Step 4](salary-discrimination-by-gender-step-4.ipynb): make the code more flexible with constants, make the code more difficult to break.
- [Step 5](salary-discrimination-by-gender-step-5.ipynb): make the graphs easier to read.
- [Step 6](salary-discrimination-by-gender-step-6.ipynb): describe the limitations of the conclusion.

Reworked sections are marked with this note:

![Rework note](./pics/rework-note.png)

## Presentation

The presentation is in [this file](./presentation.pdf).

## Running the notebooks

1. Clone this repository
1. cd &lt;folder for the cloned repository&gt;
1. Create a [Python environment](https://docs.python.org/3/tutorial/venv.html): `python3 -m venv env`
1. Activate the repository: `source env/bin/activate` (Mac and Linux), or `env\Scripts\activate.bat` (Windows)
1. Install dependencies (only once): `pip install -r requirements.txt`
1. Run the notebooks: `jupyter lab`



