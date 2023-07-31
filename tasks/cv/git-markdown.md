# CV#1. Markdown & Git
Your task is to arrange the repository according to the requirements, add your CV in markdown format to it, and deploy the CV in markdown format on GitHub Pages.

- [Job description and requirements](https://github.com/rolling-scopes-school/tasks/blob/master/tasks/cv/cv.md#%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5-cv)
- [Tips for completing a job using VS Code](cv-hints.md)
- [Tips for doing a job using GitHub](cv-github-hints.md)  

## Operating procedure
1. In your GitHub account, create a public repository named rsschool-cv. A given repository's master branch ( main) should contain only one `README.md`.
2. From branch, `main` create branch `gh-pages`.
3. In the process of working on a project, `gh-pages` at least 3 commits must be made to the branch. According to the [guideline](https://docs.rs.school/#/en/git-convention?id=examples-of-commit-names), the name of each commit must begin with one of the listed prefixes `init:`, `feat:` , `fix:` , `refactor:` , `docs:`.
4. `gh-pages` Place the file in the branch `cv.md`.
5. Using the markdown in the file, `cv.md` create your CV.
Requirements for the content of the CV and recommendations for its preparation are listed in the [assignment description](cv.md#CVcontent) .
6. In the `README.md` branch file `gh-pages`, add a link of the form `https://GITHUB-USERNAME.github.io/rsschool-cv/cv`, in which instead `GITHUB-USERNAME` specify your nickname on the GitHub site. This link should open the CV page deployed on GitHub Pages.
7. Create a Pull Request from branch `gh-pages` to branch `main`.
Name Pull Request `Markdown & Git`
[Description Pull Request give according to the scheme](https://docs.rs.school/#/en/pull-request-review-process?id=pull-request-requirements-pr) .
You don't need to merge a Pull Request from branch `gh-pages` to branch `main`.

## Publish resume on github-pages(Deploy)
To find the link to the resume you posted earlier (and add it to the third paragraph of the pull request description):

- being in your repository, find the block on the right side `Environments`(as a rule, it is located in the lower corner); github
- click on github-pages(near the rocket icon🚀) and in the window that opens, click on View Deploymentat the same time the site with your resume should open; github
- the service gh-pagesallows you to publish your content on the Internet (i.e. it becomes public and anyone can see it), files with the extension are used as content .md, however, if there is a file with the extension in the root of the repository, index.htmlthen it will be used as the main page because has a higher priority than .mdfiles;
- the first task (CV#1) is checked automatically - for this, our bot goes to the repository page and checks the correctness of the commit prefixes, their number (should be more than three), the name of the PR and that its items are filled. Then in a week, at the cross-check stage, the layout of the task (CV # 3), completed using html / css, will be checked. Note: in the third paragraph of the pull request, you can specify a link to an already made-up resume (using HTML/CSS);
- [Deploy to GitHub Pages](https://www.youtube.com/watch?v=I-yT2Err6PE&ab_channel=KahanDataSolutions)

## How to submit a task
- After finishing work on the task, go to rs app https://app.rs.school/ , select Auto-Test , select the name of the task in the drop-down list, click the Submit button . The test result will be displayed on the right. The result (score, accuracy, details) may not be displayed immediately (processing time). If there are zeros and gaps after the submit, you can refresh the page with the results (using the refresh button).
- Before the deadline, you can submit the task as many times as you like, each subsequent submission overwrites the previous one.
- NB! If the error "Error: Temporary Github Error. Cannot get commits. Please try in 10 mins." this means that the system is overloaded and cannot get information about your commits from GitHub (the request limit has been reached). No need to correct the work, you need to try to submit the task a little later and repeat attempts until a successful upload or deadline, whichever comes first.

## Criteria for evaluation
**Maximum score for the task +100**
- the requirements for the +50 repository have been met;
- the requirements for commits and Pull Request +50 are met.

## Materials:
- [Working with Git](git.md).
- [Markdown Syntax Cheat Sheet](https://ydmitry.ru/blog/rukovodstvo-po-markdown-dlya-uproshcheniya-veb-razrabotki/). .