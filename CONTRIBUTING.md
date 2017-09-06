# How to contribute to the Santa Cruz Machine Learning Cooperative

The Santa Cruz Machine learning cooperative has a lot of ways for you to contribute!

[Fork it now!](https://github.com/santacruzml/coop#fork-destination-box)!

Check out the project's [Issues Page](https://github.com/santacruzml/coop),
which we use as a discussion forum. Issues which should in this repository can be voted on and resolved using
Pull Requests!

If you don't see an issue you can contribute to, feel free to [create your own](https://github.com/santacruzml/coop/issues/new)!

## Contributions and Pull Requests

GitHub pull requests should be used to contribute to the project repository. 
GitHub provides a nice [overview on how to create a pull request](https://help.github.com/articles/creating-a-pull-request).

Some general rules to follow:

* [Fork](https://help.github.com/articles/fork-a-repo) the main project 
  into your personal GitHub space to work on. [Fork it now!](https://github.com/santacruzml/coop#fork-destination-box)!
* Clone that fork to your local computer `git clone https://github.com/YOURNAME/coop.git` 
* Set `santacruzml` as your upstream repository `git remote add upstream https://github.com/santacruzml/coop.git`.
* Create a branch for each update you are working on referencing the
  related issue in the branch name. `1_profile` was a branch to add our
  profile image to the repository. `git checkout -b 12_my_addition`.
* Make commits using `git commit -m "my addition"`.
* Feel free to use long commit messages to describe your addition, however
  please limit the first line to 80 characters.
* You can use the special comment in your commit message `"Close #12"`, 
  which will reference the issue related to your commit and help to make
  sure it gets closed.
* Upload your changes to your fork using `git push origin 12_my_addition`.
* Create a pull request against the `santacruzml/coop:master` branch using
  your newly pushed branch.

If your Pull Request is accepted you can update your local master branch
using `git pull upstream master`. Then, when you create new additions you
will be using the latest code.

### Squashing commits

When your Pull Request is accepted your commits will be "squashed" into 
a single commit against the `master` branch. You don't have to do this 
yourself, it will be done by the person performing the merge.

## Voting

Once a pull request or issue have been submitted, anyone can comment or vote 
on an issue to express their opinion following the Apache voting system. 
Quick summary:

- **+1** something you agree with
- **-1** if you have a strong objection to an issue, which will be taken very 
  seriously. A -1 vote should provide an alternative solution.
- **+0** or **-0** for neutral comments or weak opinions.
- It's okay to have input without voting
- Silence gives assent

A pull request with no **-1** votes is ready to be merged. The merge should be 
done by someone from a different organization than the submitter.

If an issue gets any **-1** votes, the comments on the issue need to reach 
consensus before the issue can be resolved one way or the other. There isn't 
any strict time limit on a contentious issue.

In case a merge happens too quickly, closed pull requests can also get 
**-1** votes, which will always need to be resolved. 

The project will strive for full consensus on everything until it runs into 
a problem with that model.

