Steps to Create repository in GitHub

Steps to create a Git repository named after your enrollment number and add the required folders:

1. Initialize a New Git Repository
Open your terminal or command prompt and run:
mkdir 2302031000015 
cd 2302031000015
git init

2. Create the Required Folders
Inside the repository, create the Assignment_1 and Assignment_2 folders:
mkdir Assignment_1 Assignment_2
Since Git doesn’t track empty folders, add a placeholder file:
touch Assignment_1/.gitkeep
touch Assignment_2/.gitkeep

3. Stage and Commit the Changes
Now, add the folders to Git and commit:
git add .
git commit -m "Added Assignment_1 and Assignment_2 folders"

4. Create a Remote Repository on GitHub
  1. Go to GitHub and sign in.
  2. Click New Repository and name it 2302031000015.
  3. Copy the repository URL (e.g., https://github.com/Nilkanth-12/2302031000015.git).

5. Link Local Repository to GitHub
Run the following command to add the remote repository:
git remote add origin https://github.com/Nilkanth-12/2302031000015.git
Verify the remote link:
git remote -v


6. Push the Repository to GitHub
Finally, push your local repository to GitHub:
git push -u origin main
Done!

Your repository now contains two folders, Assignment_1 and Assignment_2, and is successfully pushed to GitHub.
