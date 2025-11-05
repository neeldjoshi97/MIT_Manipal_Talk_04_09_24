# Guest Talk at Dept. of Mathematics, MIT Manipal

An interactive guest lecture for undergraduate students in the [Department of Mathematics](https://www.manipal.edu/mit/department-faculty/department-list/mathematics.html) at [MIT Manipal](https://www.manipal.edu/mit.html) that combined brief, engaging talks with hands‑on activities using Jupyter Notebook to introduce core mathematical concepts, demonstrate practical computational tools, and highlight considerations for transitioning from academia to industry. Topics include **Eigenvectors, Transforms, Responsible AI, FinTech, Blockchain, Game Theory**, and **Network Graphs**.

**Goals**
- Spark early interest in mathematics through playful, accessible problem-solving.
- Illustrate practical applications and computational approaches.
- Encourage collaboration, curiosity, and continued self-study.

**Format & materials**
- 45–60 minute session combining a brief lecture, 2–3 guided tasks, and an open Q&A.
- Accompanying resources (slides, example notebooks, datasets, and scripts) are provided in this repository to support follow-up exploration.

**Intended outcomes**
- Improved intuition and confidence with mathematics, plus concrete next steps and resources for students who want to explore further.
- A set of reproducible materials instructors and students can reuse or adapt for similar outreach events.

## Table of Contents

- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [License](#license)  
- [Contact](#contact)

## Getting Started

Make sure that you have latest version of `Python3.0` installed on your local machine (or cloud environment). For this lecture, I used `Python 3.12.10`.

1. Clone this repository on your local machine or cloud environment. You can also use the following `bash` command.
    ```
    git clone https://github.com/neeldjoshi97/MIT_Manipal_Talk_Data_4_9_24.git mydata
    ```
    This will save the contents in a folder called `mydata`.
2. Run the following command on the terminal 
    ```
    pip install -r requirements.txt
    ```
3. Open the `Mathematics_for_Cool_Tasks_Master.ipynb` file in an IDE (e.g. VS Code) or on Jupyter Labs.

## Usage

Open the slides included with the repository (since the programming part is interwined with the talk) and follow along with the Jypter Notebook whenever the slides tell you to do so.

After you are done with the task, continue from where you left off at the presentation.

Play around with the parameters and try to reason with yourself on what happens when you change something. E.g. the graph network stored in `network_1.txt` is a very short one with few nodes, whereas the one stored in `network_2.txt` is a very large one (more than a thousand nodes). It can be seen by comparing the file sizes. What happens when you plug in the large network into the code? What difference did it make to the outputs?

## License

This repository is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially
Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made.


## Contact

For queries, shoot an email to neeldjoshi@gmail.com
