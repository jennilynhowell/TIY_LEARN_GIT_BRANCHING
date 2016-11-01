GIT EXERCISES

Requirements

  Without editing the files (only use git branch, git rebase, etc.), make the required changes to your fork of the assignment repository. You will be using and rearranging the 6 commits in the master branch to complete the exercises.

Tasks

  1. Fork repository learn-git-branching: https://github.com/tiy-greenville-frontend-2016-feb/learn-git-branching
  2. Clone forked repository (create a local project folder)
  3. Create branch called exercise-1. Contents of branch should ONLY include boilerplate code and heading.
     HINT: use git checkout
  4. Create branch called exercise-2. Contents of branch should ONLY include boilerplate code and anchor tag.
     HINT: use git checkout and git cherry-pick
  5. Create branch called exercise-3. Contents of branch should include all master content (all commits), as well as an h2
     tag.
     The h2 should appear directly after the h1 tag and contain your name.
     The h2 tag should have its own commit; the commit should appear in history (git hist) after the heading commit.
     HINT: use git interactive rebase
  6. Create branch called exercise-4. The contents of the branch should be index.html with all of the content from
     master,except the paragraph of text should be removed from the page without being removed from the branch's history.
     HINT: use git commit --amend
  7. Publish exercise-3 to gh-pages
     HINT: Make sure exercise-3 is checked out, then create gh-pages branch
  6. Push all branches to github
     HINT: use git push origin --all
