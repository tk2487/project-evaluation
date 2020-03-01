
# A Project Evaluation Activity

## Summary
This repository contains a template to be used for evaluating FOSS projects.
The template is named `evaluation_template.md`, and contains
a questionnaire to be completed for each project that you evaluate.

<!--
In class you will evaluate a single project.
You may be asked to evaluate one or more
additional projects using this same template.
-->

For each project that you evaluate, you will copy the template and name the copy
with the name of the project followed by `_evaluation_NUM.md` where `NUM` indicates the evaluation number (since there may be more than one evaluation of the same project completed by different persons and/or teams). <br>
For example if you evaluate a project named `Go` (and there is no evaluation of `Go` yet) and a project
named `sketchy` (and there are already two evaluations for that project),
you would copy the template into two files named `Go_evaluation_1.md` and
`sketchy_evaluation_3.md` respectively. <br>

To do any evaluation at all, you will fork and clone this repository, and
create a new branch named with the project you will evaluate. Details are below.

## Detailed Steps

1. You will be given a project to evaluate as the first step. In these
instructions we will assume the name of the project is `fuzzball`.

1. You might be working individually or as part of a team, depending on whether
this is an in-class or a homework exercise. These instructions will call you
a team, even if you are a team of size one.

1. One member of the team begins by forking this repository to their own
GitHub account, and cloning the fork to their local machine. Only one person
should do this. That person will act as the editor of the file.

1. Once the repository is cloned to the local machine, you should create an
upstream remote that points to this original repository:

   ```
    git remote add upstream https://github.com/nyu-ossd-s20/project-evaluation.git
   ```

1. Then you should create a new branch named `fuzzball`
(or whatever your project's name is), do all  work  in that new branch.
To create the branch and check it out simultaneously using Git, use the command

   ```
     git checkout -b fuzzball
   ```

1. Having done this, the next step is to copy the file named `evaluation_template.md`
to a file named `fuzzball_evaluation.md`.

1. At this point the file should be put under Git's control:

    ```
    git add fuzzball_evaluation.md
    git commit -m "Created copy of template into fuzzball_evaluation.md"
    ```
    (Make sure that the comment above is appropriate for your project. It should not
    talk about `fuzzball`. )
    <!--
    1. Add an entry to the table on the page of the class wiki named __Project Evaluations__
    listing the name of the project in the first column and a list of the
    __actual names__ of the people in your team, not their GitHub names, in the third
    column. Leave the middle column empty for now.
    -->

1. If more than one person is in the team, the team should work on
answering the questions as the team (otherwise the team members do not get a full
picture of the project).
Answer all the questions in the template based on the information on the project
website, in `OpenHub.com` if needed, and in the project repository (DO NOT use a search engine!!!).

1. You might want to update the file periodically in Git so that you do not lose
work and can back up to a previous edit if you need to. Just stage and commit
as you go along.

1. When the evaluation is complete, stage it one last time and commit it.

1. [OPTIONAL] Since you are not working in the master branch you do not have to synchronize
with the upstream, but if you want to do so anyway, you would pull its most recent
version of the master branch into your repository:

    ```
    git checkout master
    git pull upstream master
    ```
    If you do that, you can get back to the `fuzzball` branch by running

    ```
    git checkout fuzzball
    ```

1. Now you need to push your `fuzzball` branch to your fork:

    ```
    git push origin fuzzball
    ```

1. It is time to issue a __Pull Request__ to the owner of the upstream, yours truly.
On GitHub click the `Pull Requests` tab. Click the green `Pull Requests` button.
The _base_ and _head_ repositories should be correct by default.
The base is the original repository, and the head is your fork of it.

    For the `compare` branch, select your
    project branch, namely `fuzzball`. Click the green `Create Pull Request` button.
    When the window changes, set a title for the Pull Request:
    "Submitting Evaluation of Fuzzball" (again make sure to replace the name of the project
    with your own project) and write some comment in the comments box and then submit.


1. After the Pull Request is accepted and merged, you should synchronize again
with the upstream:

    ```
    git checkout master
    git pull upstream master
    ```

1. You should see your evaluation file, `fuzzball_evaluation.md` in the master
branch. If you do not, send a comment. Otherwise you can safely delete your topic
branch locally and from the origin (i.e., your fork):

    ```
    git branch -d fuzzball
    git push -d origin fuzzball
    ```
   and synchronize your fork with the upstream:

    ```
    git push origin master
    ```


<!--

1. Go back to the page of the class wiki named __Project Evaluations__
and put a link in the middle column to your file in this
`project-evaluation` repository.

1. You are finished.

-->
