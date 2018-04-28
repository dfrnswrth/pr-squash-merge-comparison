Squash Merge
============

Pull Request Merge Method Comparison
------------------------------------

There was one merge conflict with this method:

```
<<<<<<< branch3__from_branch2
branch 2

* a change from branch 3
=======
branch 2
>>>>>>> master
```

```
$ log --graph --decorate --format=oneline --abbrev-commit --all
* bfb736f (HEAD -> master, origin/master, origin/HEAD) branch 5 (#6)
* 2390923 Revert "branch 4 (#4)" (#5)
* 47c569d branch 4 (#4)
* e7b35b5 Branch3  from branch2 (#3)
* 8eed7f9 branch 2 (#2)
* e34f426 branch 1 (#1)
* f23cea3 initial commit - create README.md
```
