# Assignment-pre-series04-python

**Signal derivative, tangential speed and interactive plot**

The objective of this assignment is to generate a known 3D signal (x, y, z), estimate its time derivative with two numerical methods (forward and central difference), compute its tangential speed in any number of dimensions, and display the signal and its speed in an interactive plot. The assignment was given by Denis Mottet as part of the IEAP master's programme.

## Group Members & Contributions

Each member worked on their own section in a separate notebook stored in the `Sections` folder. The sections were then combined into one final notebook, exported as an HTML file and uploaded on Moodle.

| File | Member | Contribution |
|---|---|---|
| `Sections/section_1.ipynb` | Jeanne Le Roux | Sections 2 and 3 – Generation of a known signal (time vector, 3D sinusoid, 2D and 3D plots), math of the time derivative, forward and central difference functions, comparison with the analytical derivative,  creation of the readme |
| `Sections/section_2.ipynb` | Sarah Durand | Section 4 - Creation of the public repository – Tangential velocity vs tangential speed, formulas in 3D and nD, `tangential_speed` function and test cell from 1D to 4D, export as a zoomable HTML file |
| `Sections/section_3.ipynb` | Shakir Nasir | Section 5 – Interactive plot of the signal and its tangential speed with plotly |
| `<final notebook>.ipynb` | Group | Final integrated version containing the completed work |

## Project Objectives

- Generate a 1 Hz sinusoid along three axes, with a phase shift between x, y and z.
- Write the math of the time derivative of a sine wave (in LaTeX).
- Explain and code the forward and central difference methods.
- Distinguish tangential velocity (a vector) from tangential speed (a scalar).
- Write the formula of the tangential speed in 3D and in nD.
- Code a function that computes the tangential speed and test it with `assert` statements.
- Create an interactive, zoomable plot with plotly.
- Work collaboratively using Git and GitHub.

## Project Structure

```
Assignment-pre-series04-python/
│
├── Sections/
│   ├── section_1.ipynb        (sections 2 and 3)
│   ├── section_2.ipynb        (section 4)
│   └── section_3.ipynb        (section 5)
├── <final notebook>.ipynb     (all sections combined)
├── <final notebook>.html      (file uploaded on Moodle)
├── part5_interactive_plot.html
├── .gitattributes
├── LICENSE                    (MIT)
└── README.md
```

## Git and GitHub Workflow

We worked in turn, each member building on the work of the previous one. Jeanne first generated the signal and coded the derivative functions (sections 2 and 3). Sarah then reused the `central_difference` function to compute the tangential speed (section 4). Finally, Shakir reused the signal and the `tangential_speed` function to build the interactive plot (section 5). After each step, the next member reviewed the previous work and left comments to correct errors before continuing, and the changes were merged into the main branch through Pull Requests.
 
This workflow allowed us to:
 
- Build each part on code that had already been checked.
- Reuse the same signal and functions throughout the notebook, instead of redefining them.
- Keep track of each contribution.
- Review and improve each other's work.


## What We Learned

- Create time vectors and multi-dimensional signals with NumPy.
- Write math in LaTeX inside a Jupyter notebook.
- Estimate a derivative numerically and compare the accuracy of two methods.
- Generalise a formula from 3D to nD before coding it.
- Test a function with known signals and `assert` statements.
- Build an interactive plot with plotly and export it as HTML.
- Share and review work through a GitHub repository.

## How to Use This Repository

Clone the repository to your computer:

```
git clone https://github.com/sdurand875-spec/Assignment-pre-series04-python.git
```
