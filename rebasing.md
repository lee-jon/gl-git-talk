# Rebasing

## Rebasing as if we were cherry-picking

We're in this situation

			 A---B---C rebase
			/
	   D---E---F---G part2

`git cherry-pick G`

			 A---B---C---G' rebase
			/
	   D---E---F---G part2

If I wanted everything I could do

`git cherry-pick E F G`

to get this

			 A---B---C---E'---F'---G' rebase
			/
	   D---E---F---G part2

## What is rebasing?

The problem is this pulls them on top of my files but they're essentially older.


			 A---B---C rebase
			/
	   D---E---F---G part2

Rebase allows us to move the branch point.

                   'A---'B---'C rebase
                  /
	   D---E---F---G part2
