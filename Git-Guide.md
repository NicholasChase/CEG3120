<h1>The Git Guide</h1>

<h3>Git Usage and command</h3>
<ul>
  <Li>Add: git add [file], add a file to your next commit</li>
  <Li>Commit: git commit -m "Insert message here", commit your staged contennt as a new commit snapshot</li>
  <Li>Push: git push [alias]/[branch], transmit local branch commits from the tracking remote branch</li>
</ul>

<h3>What causes a pull request</h3>
<ul>
  <li>Pull request: git pull, fetch and merge any commits from the tracking remote branch</li>
 </ul>
<p>Pull request is a Git branch pushed to a remote Git repo</p>


<h3>How to create an issue and how to resolve an issue</h3>
<h4>Issues</h4>
<ul>
  <li>gh issue create [flags]</li>
  <li>ex: gh issue create -- title "Found a bug" --body "Nothing is working" </li>
 </ul>
 <h4>Options</h4>
 <p> -a, --assignee login   Assign people by their login<br>
  -b, --body string      Supply a body. Will prompt for one otherwise.<br>
  -l, --label name       Add labels by name<br>
  -m, --milestone name   Add the issue to a milestone by name<br>
  -p, --project name     Add the issue to projects by name<br>
  -t, --title string     Supply a title. Will prompt for one otherwise.<br>
  -w, --web              Open the browser to create an issue<br></p>

<h4>Resolve Issues</h4>
<p>You can only resolve merge conflicts on GitHub that are caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository.</p>
<h5>Steps to resolve</h5>
<ul>
  <li>Step 1: When there is a conflict merging code to the GitHub repo, user may go into the "Resolve Issue" tab</li>
  <li>Step 2: After user reviews the conflict, user will decide which conflicting code will stay and which will go</li>
  <li>Step 3: After determining which code will stay, user will then click on the "Mark as Resolved" button</li>
  <li>Step 4: Next click on the green "Commit Merge" button</li>
  <li>Step 5: Next Click on the Green "Merge Pull Request" button near the bottom of the page and confirm button</li>
</ul>




<h4>Useful Links</h4>
<p>
<ul>
  <li>Git Cheat Sheet: https://education.github.com/git-cheat-sheet-education.pdf</li>
  <li>Git Issue Manual: https://cli.github.com/manual/gh_issue_create</li>
  <li>Git Issue Resolve Definition: https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github</li>
  <li>Steps on resolving issue: https://www.youtube.com/watch?v=JtIX3HJKwfo</li>
</ul>
</p>
