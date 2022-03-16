# DBF Junior Developer Challenge

The DBF Junior Developer Challenge is a coding challenge for applicants to junior positions at the Department of Banking and Finance, University of Zurich. We think that it is fairer and more realistic to judge the capabilities of applicants with a small task, rather than asking theoretical questions about technical topics.

If you seek more information about us and what we work on at the DBF, check out <https://joinus.vercel.app>!

Remember: It is okay to use Google to complete the challenge, you don't need to know everything by heart!

## Application Process

When you apply for a job at our department, you will:

- Part 1: Write some Python code that simulates a simple e-Assessment task :robot:
- Part 2: Answer 2 practically-oriented questions :pencil2:
- Part 3: Reflect on your work and the challenge :thought_balloon:
- Finally: Send us the results of your challenge for a quick evaluation and feedback :outbox_tray:

Everybody that completes the challenge with a good standard (it does not have to be perfect) gets invited to a job interview. The challenge allows us to focus more on alignment of interests and your cultural fit rather than asking you a lot of technical questions :bell: However, we will most certainly talk to you about the challenge and your responses.

## Part 1 - Python and Excel

### Requirements

- Python 3.8+ and Pip
- Git (optional)

### Preparations

- If you have Git installed and know the basics, fork the repository on Github and push your work/commits
- If you have no prior knowledge of Git, download the ZIP file from Github and submit us a ZIP of your solution
- Install Python dependencies using `pip install -r requirements.txt` (or use Poetry if you are familiar)

### Task Description

Your task is to create a Python software that creates individualized student files based on a template of the upcoming computer science exam. You have been given some skeleton code, and are tasked with adding program code to `modules/processor.py` according to the specifications given in the comments.

Your command-line program should be runnable using `python main.py`.

## Part 2 - Quiz

Select two out of the following three questions and write a short response (a few sentences each). You can edit this README directly, or add your responses to a new file.

- [ ] What is the difference between Openpyxl and Xlwings? Why and when would you use one over the other?
- [ ] What are the advantages of using a dependency management package like Pipenv or Poetry?
- [ ] What does the following code snippet do? What might be wrong with it? What could be done better?

```python
Name_path = os.path.join(some_folder_name, some_file_name)
if os.path.exists(Name_path) is True:
    console.print(
        f"ERROR: The path {Name_path} is missing.\nINSERT THE some_file_name IN THE {some_folder_name} FOLDER",
        style="black",
    )
    exit()
```

## Part 3 - Reflection

Reflect on your work on this challenge and add your responses below, or save them in a new file.

- [ ] How did you approach this task? Try to formulate a few sentences.
- [ ] How did you like this challenge? Is there anything unclear or anything else that we could/should improve?

## Checklist

All done? Please make sure you have completed everything in our application checklist:

- [ ] Forked this repository.
  - Create a private fork if you do not want to make your results publicly available.
- [ ] Implemented the requirements for Part 1 and saved/committed your code.
- [ ] Answered 2 questions and saved/committed your answers.
- [ ] Reflected on your work and saved/committed your answers.
- [ ] Share the link to your repository with us when applying.
  - Add `rschlaefli`, if you do not want to make your repository publicly available.
- [ ] Submitted the application form on [joinus](https://joinus.vercel.app/).
