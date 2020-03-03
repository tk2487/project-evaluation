Project Name: OpenEMR
=====================

**Evaluating Person or Team**: Quang @quangio ---

Project Data
------------

1.  Project description: Electronic health records and medical practice
    management solution

2.  Project website/homepage: <https://www.open-emr.org/>

3.  Project repository: <https://github.com/openemr/openemr>

License
-------

1.  What is the project\'s license? GPLv3

Code Base
---------

1.  What is the primary programming language in the project?

    PHP

2.  What is the development environment?

    LAMP or Docker

3.  Are there instructions for how to download, build, and install? How
    easy is it to find them? Do they seem easy (relatively speaking) to
    follow?

    The README file has one and the Contributing has another. It is
    straight forward LAMP style web application.

4.  Does the project depend on external additional software modules such
    as database, graphics, web development, or other libraries? If so,
    are there clear instructions on how to install those?

    Require LAMP and NodeJS. Or just `docker-compose up`

5.  Is the code easy to understand? Browse some source code files and
    make a judgment based on your random sample.

    Typical PHP CRUD style. But it\'s quite difficult to reason about
    correctness and relationships.

6.  Is this a big project? If you can, find out about how many lines of
    code are in it, perhaps on [OpenHub](https://www.openhub.net/).

    \~2M LoC. Big project.

7.  Does the repository have tests? If so, are the code contributors
    expected to write tests for newly added code?

    Yes. But not a requirement for contributors.

Code and Design Documentation
-----------------------------

1.  Is there clear documentation in the code itself?

    Yes

2.  Is there documentation about the design?

    [Yes](https://github.com/openemr/openemr/tree/master/Documentation)

Activity Level
--------------

1.  How many commits have been made in the past week?

    \~75

2.  When was the most recent commit?

    Mar 1 8pm EST

3.  How many issues are currently open?

    242

4.  How long do issues stay open?

    \~1 day. Some issues did take quite long however.

5.  Read the conversations from some open and some closed issues. Is
    there active discussion on the issues?

    There are lots of comment bubbles

6.  Are issues tagged as easy, hard, for beginners, etc.?

    The system exists but is not really used.

7.  How many issues were closed in the past six months?

    [100](https://github.com/openemr/openemr/issues?utf8=%E2%9C%93&q=is%3Aissue+closed%3A%3E%3D2019-09-02+)

8.  Is there information about how many people are maintaining the
    project?

    A lot. But I would say around 10 people are actively involved

9.  How many contributors has the project had in the past six months?

    \~25

10. How many open pull requests are there?

    94 open + 2173 closed

11. Do pull requests remain un-answered for a long time?

    No. They are merged quite quickly. \~1 day.

12. Read the conversations from some open and some closed pull requests.
    Is there active discussion on the pull requests?

    Yes. There are bubbles.

13. How many pull requests were opened within the past six months?

    [24 Open + 238
    Closed](https://github.com/openemr/openemr/pulls?utf8=%E2%9C%93&q=sort%3Acreated-desc+created%3A%3E%3D2019-09-02)

14. When was the last pull request merged?

    Mar 1 4pm EST

Welcomeness and Community
-------------------------

1.  Is there a CONTRIBUTING document? If so, how easy to read and
    understand is it? Look through it and see if it is clear and
    thorough.

    Yes. Easy to read.

2.  Is there a CODE OF CONDUCT document? Does it have consequences for
    acts that violate it?

    Yes. You can get banned basically.

3.  Do the maintainers respond helpfully to questions in issues? Are
    responses generally constructive? Read the issue conversations.

    Yes.

4.  Are people friendly in the issues, discussion forum, and chat?

    Yes.

5.  Do maintainers thank people for their contributions?

    Yes.

Development Environment Installation
------------------------------------

Install the development environment for the project on your system.
Describe the process that you needed to follow:

1.  how involved was the process?

    Need some DevOps skills (I used the non-docker method).

2.  how long it take you?

    20 minutes, speed run

3.  did you need to install additional packages or libraries?

    Yes

4.  were you able to build the code following the instructions?

    Yes. But need to install php extensions and setup the database
    myself.

5.  did you need to look for additional help in installing the
    environment?

    No.

6.  any other comments?

    [Known
    vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-12269/product_id-23156/Open-emr-Openemr.html)
    (most of them are high/critical issues)

Summary
-------

1.  Do you think this is a project to which it would be possible to
    contribute in the course of a few weeks before the end of this
    semester?

    Yes. The Installation (like the php install.php not the actual
    deploy) can be improved for example.

2.  Would you be interested in contributing to this particular project?

    No. PHP bad.

    On serious note, I have no interest in maintaining an old CRM/CMS
    system and am not willing to write PHP. It seems the project does
    not have an open bug bounty program either.
