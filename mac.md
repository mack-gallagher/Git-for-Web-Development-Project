## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?

  Git is a software tool that allows multiple developers working on different computers to contribute edits to the same software project without stepping on each others' toes. This is enabled by providing a standard interface for all of the developers to work on their own local versions of a project, and periodically push their edits, or decide to incorporate others' edits, into a central version of the project, which Git automatically organizes so it actually makes sense and works.

2. What is the difference between Git and GitHub?

  Git is an open source version control tool that can be implemented in multiple ways. GitHub is a for-profit company that provides popular cloud hosting for developers to use Git over their website. You do not need to use GitHub to use Git, but every time you use GitHub, you are using Git.

3. Why do we create a branch?

  If you are working on some changes to Aspect A of a project, and at the same time working on some other changes to Aspect B, and you're not sure whether you're going to end up wanting to keep the changes to Aspect A, you'll be a lot better off if, when it comes time to push the changes you made to Aspect B with the main project, you *don't* also have to push incomplete changes to Aspect A. This is why it would come in handy to be making your speculative changes to Aspect A of the project in a separate branch. Branches in general help keep different streams of editing separate from one another, so code can be merged cleanly and all-at-once.

4. What is the purpose of a Pull Request?

  If a lot of people are working on a software project, giving them all permission to push to the main branch would be a disaster. So, in Git, non-administrators of a project can submit requests for their proposed edits to be incorporated ["pulled"] into the main project. These requests can be reviewed and approved or rejected by project administrators who keep the main project on track.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.

  I can use `git checkout mack-gallagher` to switch into the mack-gallagher branch and `git checkout main` to switch back into main.
  
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

  `git fetch <remote>` downloads changes from a remote branch but does not integrate them into the branch you are currently working on. `git merge <branch>` merges changes from the specified branch into your current HEAD, ie the branch you [are currently working on]/[have checked out]/[are switched into]. `git pull <remote><branch>` does a `git fetch <remote>` *and then immediately* a `git merge <branch> of what you just downloaded.
  
7. What is a merge conflict?

  
8. How do you resolve a merge conflict?


