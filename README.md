# git_assignment_HeroVired
For Graded Assignment on Git and Git Hub

# Deliverable - feature -"Square Root"

A ) CalculatorPlus App 

Adding the Square root code the Calculator Plus App 

Implemented Divide function bug fix

with the final merge , delivering the App as version -2 


Added geom/rect area calculate code.

Added - geometry-calculator branch for 
merging the circle area and rect area code.


# geomcalc
added the circle area code
added the rectacngle area code
finally moved to main from dev after staging.

#lfs 

integrate Git LFS (Large File Storage) to handle
these files efficiently.
Demonstrate how to add, commit, and push binary files to the repository,
ensuring they are tracked by Git LFS correctly. Clone the repository on another
machine to verify
that the binary files are downloaded correctly.

step-1

download the large file more than 200mb , zipped it.
Installed git install lfs 

step-2 

clone the github repository to local

create the lfs branch

place the 200 mb + size file

apply command  -

git lfs track "*.zip"  ( in my case, its zip )
git add jeep1.zip
git commit -m "for upload larg
e zip file"
git push origin lfs

Ensure the zip file and other file have been reflecting at lfs branch of github side.

Now, go to another remote system  and clone the repository and ensure the large files from lfs branch are downloaded.







