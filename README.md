# DevOps_test-repo

Testing repository.

	
## Merge branches using Github Actions

This repository hosts a static website using Gihub Pages, we have two branches, 'main' and 'testing'. The goal was to automate the merge process to main branch from other branches and have the changes reflected on Github pages. I archived this via Github Actions, used a premade action from the marketplace which is devmasx/merge-branch and has to adjust it to match my repo. The way its set, everytime we push changes to the "testing" branch it will automatically merge with the "main" branch and also will automatically reflect the changes made in Github Pages.


