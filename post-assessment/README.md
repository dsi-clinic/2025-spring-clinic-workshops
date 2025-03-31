# Post-assessment

This assessment tests your proficiency with team-based programming workflows, including: cloning a Git repository; checking out a feature branch; running scripts; staging, committing, and pushing changes; and finally, opening a pull request for another individual to review.

Complete as many of the following steps as you can within the next 10 minutes _using only the terminal_.

1. Open a new terminal window.

2. Navigate to the directory `clinic-workshops` under your user account folder (i.e., `/Users/<your-os-username>` on MacOS and `/home/<your-os-username>` on Windows WSL). Then under that directory, create a directory called `post-assessment`.

3. In the `post-assessment` folder, clone the GitHub repository **[2025-spring-clinic-workshops](`https://github.com/dsi-clinic/2025-spring-clinic-workshops`)** using SSH authentication.

4. Open the cloned GitHub repository in VS Code.

5. Open a new terminal window _in VS Code_ and close your previous terminal.

6. Switch from `main`, the default branch, to a new branch named `post-assessment-<your-github-username>`. For example, my GitHub username is `LaunaG`, so my branch would be `post-assessment-LaunaG`.

7. Change your current working directory to `post-assessment`. Make a new folder called `cities` and add a text file called `favorite_cities.txt`. Add your three favorite cities to the file (e.g., `Chicago, Paris, and Lagos`) and double check that the file contains the new information.

8. Run the bash script `print_shell.sh`. This should output a new text file called `my_shell.txt` containing the path to your system's configured shell (e.g., `/bin/bash`).

9. Move the file `big_cities.csv` to the `cities` folder.

10. Remove the file `lost_cities.csv`.

11. Stage your changes and then commit them with the message `Finishes post-assessment.`

12. Push your changes to a new remote version of your branch, hosted on GitHub.

13. Create a new pull request from your branch into `main`. Write a descriptive message and assign Jim Pivarski (GitHub username: `jpivarski`) as your reviewer.
