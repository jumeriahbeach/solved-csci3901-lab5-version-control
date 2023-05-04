Download Link: https://assignmentchef.com/product/solved-csci3901-lab5-version-control
<br>
In this lab, you will explore the version control system called Git. you will apply your knowledge of version control, notably Git, to manage a set of files for a project.

You will be given an initial configuration of Git for a project and will be asked to effect a set of changes to the files, stored in Git, to achieve a target configuration for your Git repository.

<h1>Preparation</h1>

<ul>

 <li>Download and install Git. You may use your IDE if it supports git integration, or through the command line (on windows, you may want to install Git Bash alongside Git for this).</li>

</ul>

<h1>Resources</h1>

There are many Git tutorials online that can help you. Some examples are

<ul>

 <li><a href="https://git-scm.com/docs">https://git-scm.com/docs</a></li>

 <li><a href="https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html">https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html</a></li>

 <li><a href="https://education.github.com/git-cheat-sheet-education.pdf">https://education.github.com/git-cheat-sheet-education.pdf</a></li>

</ul>

<h1>Procedure</h1>

<strong>Set-up</strong>

<ol>

 <li>Download and unzip the Git repository from Brightspace.</li>

</ol>

<strong>Lab steps</strong>

<strong>Part 1 – History </strong>Using git status, git log, git diff, and git branch answer the following questions:

<ol>

 <li>How many commits are there?</li>

 <li>What is the commit message associated with the most recent commit?</li>

 <li>Which commit added the basePrices static variable?</li>

 <li>How many branches are there?</li>

 <li>Which is the last commit on the coupons branch?</li>

</ol>

Resources: status, diff, log, branch

<strong>Part 2 – Basic operations</strong>

<ol>

 <li>Fix the 3 remaining bugs from the Debugging lab. In particular:

  <ul>

   <li>On lines 62, 64, and 66, topping == str should be equals(str)</li>

   <li>On lines 63, 65, and 67, price = should be price +=</li>

   <li>The final price should be price = price – price*coupon/100</li>

  </ul></li>

 <li>Commit these bug fixes with a suitable commit message</li>

</ol>

Resources: add, commit

<strong>Part 3 – Branching</strong>

<ol>

 <li>Create a new branch called burger. Your new branch should be off the repository’s master branch</li>

 <li>Add a new menu option for a burger. A burger at HfxDonairExpress costs $2.50</li>

 <li>Commit this change on the burger branch</li>

 <li>Finally, merge the burger branch into the main branch</li>

</ol>

Resources: branch, checkout, add, commit, merge

<h1>Questions</h1>

<ol>

 <li>When working alone on a project, how frequently should you commit your code to a version control system? Explain why.</li>

 <li>When working in a team, how frequently should you commit your code to a version control system? Explain why.</li>

 <li>Why might you create branches for your project in your version control system?</li>

</ol>