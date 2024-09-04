# greenwood-library-website
## Creating Repository on Github 
I created a repository on github and made it public.
## Cloning Repository
- I cloned the repository on my computer by using the https URL https://github.com/Berrie89/greenwood-library-website.git
and typing on the terminal git clone https://github.com/Berrie89/greenwood-library-website.git.
- It requested for my username and password, but using of password has been stopped. Instead of entering my password, I generated a classic personal access token on github.
- After the repository was cloned on my computer. I changed Directory to the repository by entering cd greenwood-library-website.
- I typed 'git remote set-url origin https://personal access token/Github username/repository' in my terminal.
- Cloning the repository gave me the main branch.
- I created the about_us.html, contact_us.html, home.html, events.html files.
## Confirm changes have been staged
- I typed git status in my terminal to check if the changes has been staged. If changes has not been changed the files would be in red and if changed, status would be green.
## Stage changes
- I typed git add filename in my terminal to stage the changes.
## Commit changes
- I commited the changes by typing git commit -m "message" in my terminal.
## Push main branch to Github
- I sent the commits from my main branch to Github by typing git push origin main in my terminal.
## Simulating Morgan's work
- I checked the list of branches in my local repository by typing git branch in my terminal.
- I only saw the main branch because that is the default starting point.
- I created a new branch for Morgan by typing git checkout -b add-book-reviews. This will create a new branch for Morgan's work and automatically switch to that branch.
- All files that were created in the main branch will also be in the add-book-reviews branch
- I created another file called book_reviews.html
- I typed git add filename in my terminal to stage the changes.
- I typed git status in my terminal to check if the changes has been staged.
- I commited the changes by typing git commit -m "message" in my terminal.
- I sent the commits from the add-book-reviews branch to Github by typing git push origin add-book-reviews in my terminal.
- I switched to the main branch by typing git checkout main in my terminal.
- I pulled the latest changes made by Morgan by typing git pull origin add-book-reviews 
## Simulating Jamies's work
- I switched back to the main branch.
- I created a branch for Jamie by typing git checkout -b update-events in my terminal. This created a new branch and automatically switched to Jamie's branch.
- I made all necessary changes.
- I typed git add filename in my terminal to stage the changes.
- I typed git status in my terminal to check if the changes has been staged.
- I commited the changes by typing git commit -m "message" in my terminal.
- I sent the commits from the update-events branch to Github by typing git push origin update-events in my terminal.
- I switched to the main branch by typing git checkout main in my terminal.
- I pulled the latest changes made by Jamie by typing git pull origin update-events.
## Merge Changes
- After both Morgan and Jamie have pushed their changes, these changes have to be reviewed and merged.
- I opened my browser and went to my github page.
- I navigated to the repository.
- I clicked on pull request, clicked on new pull request button, clicked on open pull request.
- I reviewed the changed made by Morgan and did the same for Jamie
- I entered a title and description, then clicked on create pull request button.
- After a pull request was made. I was able to merge the pull request to incorporate Morgan and Jamie's branch into the main branch.
  
  





