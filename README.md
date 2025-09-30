# anchoredmemories

UTI VR immersive story experience





I suggest Source Tree for a GUI based git manager check out system but the command line options will be down below:
https://www.sourcetreeapp.com/





1\. Install prerequisites

&nbsp;	•	Git: Download and install from https://git-scm.com/downloads

&nbsp;	•	Git LFS: Install Git Large File Storage (needed for Unity assets)

git lfs install



2\. Clone the repository



In a terminal or PowerShell:

git clone https://github.com/<your-username>/<repo-name>.git

cd <repo-name>



3\. Pulling updates



To get the latest main branch updates:

git checkout main

git pull origin main



4\. Creating and working on a branch



Always work on a new branch for features or fixes:

git checkout -b feature/<short-name>



Example:

git checkout -b feature/particle-system



Commit your changes normally:
git add .

git commit -m "Added particle system for scene"



Push your branch to GitHub
git add .

git commit -m "Added particle system for scene"





5\. Switching branches



To return to the main branch:



git checkout main





Then pull latest updates:



git pull origin main





To go back to your feature branch:



git checkout feature/particle-system



6\. Merging to main



Once a feature branch is ready:



Push the branch to GitHub.



Open a Pull Request (PR) on GitHub’s website from your branch into main.



After review, merge the PR into main.



Everyone should then run:



git checkout main

git pull origin main



7\. Notes for Unity projects



Only Assets/, Packages/, ProjectSettings/, and UserSettings/ are versioned. Other Unity folders regenerate automatically.



Large files (textures, models, scenes >100MB) are tracked with Git LFS. They will sync automatically after git lfs install.

