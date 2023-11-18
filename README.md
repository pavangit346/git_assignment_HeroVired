# git_assignment_HeroVired
For Graded Assignment on Git and Git Hub

# Deliverable - 1  (# Q1 )

A ) CalculatorPlus App 

First Calculator Plus App has been moved from Dev to main as version -1
with some math functions.

later , Adding the Square root code the Calculator Plus App 

Implemented Divide function bug fix

with the final merge , delivering the App as version -2 

# Deliverable - 2  (#Q3 )

B) Geometry Calcualtor App 
# geomcalc
added the circle area code
did the git stash to saved the changes intact 
and moved rectacngle area code 
git stash
later come back to circle areas code 
and commited the changes to feature/circle-area
again switched to feature/rectanlge-area 
commited the changes to rectangle-area.
then pushed the circle-area code and rectangle-area code one by one to
geometric-calculator branch.
again moved the app from geometric-calculator branch to dev.
At dev branch, performed the testing.
finally moved the App to main from dev.

# Deliverable - 3 ( #Q2 )

integrate Git LFS (Large File Storage) to handle these files efficiently.
Demonstrate how to add, commit, and push binary files to the repository,
ensuring they are tracked by Git LFS correctly. Clone the repository on
another machine to verify that the binary files are downloaded correctly.

step-1

download the large file more than 200mb , zipped it. Installed git install lfs

step-2

clone the github repository to local

create the lfs branch

place the 200 mb + size file

apply command -

git lfs track "*.zip" ( in my case, its zip ) git add jeep1.zip git commit -m "for upload larg e zip file" git push origin lfs

Ensure the zip file and other file have been reflecting at lfs branch of github side.

Now, go to another remote system and clone the repository and ensure the large files from lfs branch are downloaded.






