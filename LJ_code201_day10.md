# LJ Code 201 Day - 10

“Tell me and I forget Teach me and I remember. Involve me and I learn.”

Friday in class we discussed github for pair programming.

Person 1 creates a GitHub repo, hosts it on their profile, and clones it to their local repo

Person 2 makes their own copy of the repo on their own GitHub by FORKING it

Then, Person 2 clones the fork to their local repo.

Person 2 CANNOT merge their code up to the master on Person 1’s GH. Person 2 must first push their local changes to their own GH account, and then request a merge via PR from Person 1.

Person 1 CAN make an upstream connection flowing content from the GH master repo to Person 2.
In order to make this happen, P2 must:

git remote add upstream [url for P1’s repo on GH]
And then:
git remote -v
origin fetch (OR origin pull) will link to P2’s fork
upstream fetch (OR upstream pull) will link to P1’s original GH repo
git checkout master (switch to a new branch)
git pull upstream master (to sync with master repo on GH)
But, how does P2 get their github repo in sync with the other 3?
git push origin master

Also we talked about advanced layout for CSS...
