# Project Name:  OpenStreetMap


**Evaluating Person or Team**:
Jennifer Lopez || [Jen-Lopez](https://github.com/Jen-Lopez)
---

## Project Data

1. Project description: <br>
OpenStreetMap is an open source community-driven project that allows users to access, modify, and redistribute map data. The code powers up the **map of the world** that local users can improve for an accurate representation of their area.

2. Project website/homepage: [OpenStreetMap Wiki](https://wiki.openstreetmap.org/wiki/Main_Page)

3. Project repository: [OpenStreetMap Site Repo](https://github.com/openstreetmap/openstreetmap-website)



## License

1. What is the project's license? <br>
The project has a GNU General Public License v2.0.
<!--
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
-->


## Code Base


1. What is the primary programming language in the project?  <br>
The primary programming language is Ruby.

2. What is the development environment? <br>
A contributor is able to install the software directly on their ubuntu, Fedora, or MacOS based machines. Windows machines, on the other hand, will be a difficult environment to work in so it's recommended to use vagrant. Vagrant installs the software onto a virtual machine that keeps a proper development environment.


3. Are there instructions for how to download, build, and install? How easy is it
to find them? Do they seem easy (relatively speaking) to follow? <br>
The readme file has a direct link to [installation](https://github.com/openstreetmap/openstreetmap-website/blob/master/INSTALL.md) instructions, where contributors learn about the requirements needed for development. When contributors have installed dependencies, they can navigate to the [contribution](https://github.com/openstreetmap/openstreetmap-website/blob/master/CONTRIBUTING.md) file that outlines everything from coding style, documenting code, to testing. The instructions were relatively easy to find and follow.

4. Does the project depend on external additional software modules such as
database, graphics, web development, or other libraries? If so, are there clear instructions on how to install those? <br>
The project uses many external software modules (e.g. node.js modules, a PostgreSQL database, etc.) that are all clearly detailed in the installation file.

5. Is the code easy to understand? Browse some source code files and make a judgment based on your random sample. <br>
The code is not easy to understand because there is no proper documentation. One can learn syntax for ruby on their own, but it'd be hard to understand what a source code file does without any comment on it's functionality/purpose.

6. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
According to OpenHub, the OpenStreetMap website is powered by about 208K lines of code! Thus, the project is big and will continuously grow with new contributors.

7. Does the repository have tests? If so, are the code contributors expected to write tests for newly added code? <br>
Yes there are tests. There is more information on testing in the [contributing](https://github.com/openstreetmap/openstreetmap-website/blob/master/CONTRIBUTING.md) file, but overall, the tests are meant speed up deployment of new code. When adding a new feature, contributors have to create new tests that covers the new functionality.


## Code and Design Documentation
1. Is there clear documentation in the code itself? <br>
There is no clear documentation in the code, even though it is encouraged in the contributions file.

2. Is there documentation about the design?  <br>
No, there is no document on design. From one of the issue comments, they don't have many design-oriented contributors.

## Activity Level

1. How many commits have been made in the past week? <br>
Between Feb. 24 to March 3rd, there's only been 8 commits.

2. When was the most recent commit? <br>
March 2nd, 2020.

3. How many issues are currently open? <br>
373 open issues

4. How long do issues stay open? <br>
The amount of time issues remain open varies. Issues were either resolved the same day, took a week-long or even a month-long response! The average is about 2 days.

5. Read the conversations from some open and some closed issues. Is there active discussion on the issues? <br>
There is active back and forth dialogue between the issuer and the repo maintainer to determine how the issue can be resolved.

6. Are issues tagged as easy, hard, for beginners, etc.? <br>
The majority of issues are not tagged, which would make it hard to differentiate between issues as a beginner.

7. How many issues were closed in the past six months? <br>
44 issues were closed.

8. Is there information about how many people are maintaining the project? <br>
The names and Github handles of the maintainers are on the [readme](https://github.com/openstreetmap/openstreetmap-website/blob/master/README.md) file.

9. How many contributors has the project had in the past six months? <br>
There have been 22 contributors.

10. How many open pull requests are there? <br>
47 pull requests.

11. Do pull requests remain un-answered for a long time? <br>
Responsiveness to merging pull requests varies. Some pull requests were closed within the same day. Other pull requests, on the other hand, took weeks to close. So, it took an average of about 3 days. Pull requests that merge quickly are the ones that pass the tests.

12. Read the conversations from some open and some closed pull requests.  Is there active discussion on the pull requests? <br>
Similar to issues, there is also an active discussion on pull requests. Usually, discussion surrounds on what the pull request addresses and testing prior to merge.

13. How many pull requests were opened within the past six months? <br>
13 pull requests opened in the past 6 months.

14. When was the last  pull request  merged? <br>
The last pull request was merged on  March 2nd.

## Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough. <br>
Yes, the contributing document is in the repository. It's a well detailed document with sections, so it's easy to find what you need.

2. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it? <br>
Unfortunately, there is no Code of Conduct.

3. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive? Read the issue conversations. <br>
The maintainers provide guidance to each issue. There are two maintainers so it's either a response from one or the other or both. However, I did notice that at times, one of the maintainers sounds "frustrated" when replying to new feature queries/updates (e.g. "Talking about it endlessly will achieve nothing").

4. Are people friendly in the issues, discussion forum, and chat? <br>
The people who post issues and respond to them sound like coworkers so work-wise, it sounds friendly.

5. Do maintainers thank people for their contributions? <br>
No, maintainers do not thank people for their contributions.

## Development Environment Installation

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1. how involved was the process? <br>
If you're installing all the necessary software directly onto your machine, all you need to do is follow the instructions in the installation file carefully. In this case, you need to go to each software's website to download the software or use a package manager like Homebrew to install them for you. Once you have the minimum requirements, you can clone the repo. It's a lot for a beginner to handle, but I found the installation file detailed and easy enough to follow.

2. how long it take you? <br>
It took me about half an hour to try to get the development environment since I've never done this before. But other people who do have some experience with installing packages will take less time.

3. did you need to install additional packages or libraries? <br>
Yes. Most of the packages were installed using Homebrew.

4. were you able to build the code following the instructions? <br>
Yes, I was able to build the code.

5. did you need to look for additional help in installing the environment? <br>
No I just used the installation guide in the project repository.

6. any other comments? <br>




## Summary
1. Do you think  this is a project to which it would be possible to contribute
in the course of a few weeks before the end of this semester? <br>
This is a project that can be *possible* but **challenging** to contribute to at the end of the semester. It requires foundational knowledge of Ruby and the repository, along with the source code files, is very disorganized. Although resources for installing the development environment is well documented, it requires a lot of dependencies and modules that can go above the head of a new contributor. Overall, this project left the impression that it's not beginner friendly.

2. Would you be interested in contributing to this particular project? <br>
  Personally, I would not like to contribute to this project. First of all, the primary language used is Ruby, which is something I don't have experience with. Even if I tried to learn, the source code isn't properly commented to help future contributors. Most importantly, the project does not have a code of conduct or guidelines for behavior. This raises a red flag since the safety/well-being of contributors is not valued.
