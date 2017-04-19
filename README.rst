This is developer documentation for Caktus developers.

To read the formatted documentation, visit http://ironfroggy.github.io/coding-notes/.

To make changes:

* Make a branch from the ``gh-pages`` branch.
* Make your changes.
* Push your branch.
* Open a pull request against the ``gh-pages`` branch.
* When approved, merge to ``gh-pages``.

Then additional steps are required to update the published
documentation:

* Check out the latest ``gh-pages`` branch.
* ``make html``.
* Use ``git status`` and see if there are any new output files.
  If so, ``git add`` them.
* Commit all the changes.
* Push the updated ``gh-pages`` branch to Github.

Within a few minutes, the changes should appear at
http://ironfroggy.github.io/coding-notes/.
