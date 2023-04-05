# language-english-quiz-template
A project outline tutorial for students

# Project Setup

These steps should work on Windows, Linux, or Mac OS

1. Clone this repo. Open a terminal and change directories to your project directory.

```bash
mkdir -p projects # only needed first time

cd projects

git clone https://github.com/milljohn/language-english-quiz-template.git
```
2. Create a virtual environment
```bash
cd language-english-quiz-template

python3 -m venv venv # creates the virtual environment

source venv/bin/activate # activate the environment

pip install --upgrade pip # upgrade pip to the latest

pip install -r requirements.txt # install dependancies
```

3. Open folder in VS Code

At this point, the project should be setup in VS Code.

## Pushing changes
Each time you add a feature or reach a milestone, you should push your changes. This can help track down bugs later on. It is importaint to get into this habit.

Each time you want to push a change follow these steps:

1. In VS Code, press ``control + ~ `` or ``ctrl + ~``
2. In the terminal 
```
git add <filename-you-just-changed>

git commit -m "Give a breif description of the change"

git push
```

Sometimes you want to push several files. Do this:
```bash
git add . # this will add all files in the directory, so be careful.
```

# Background

# Project Notes


