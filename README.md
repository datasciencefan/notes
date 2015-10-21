# notes
#p = "C:\\Users\\twong\\Documents\\GitHub\\Berkeley Emissions and Crime"
#setwd(p)
#df = read.csv(file = "Crime_Incidents.csv",header=TRUE)

#require(stringr)
#e = str_split_fixed(df$Block_Location, "\\(", 2)
#df$block = e[,1]
#df$location = e[,2]
#df$location = gsub("\\)","",df$location)

#git github notes
Make sure you can launch your editor from the command line

It will be helpful to be able to launch your text editor from the command line. See here for instructions on how to do this for Sublime: https://www.udacity.com/wiki/ud775/sublime. If you have trouble getting this working, videos at the end of the lesson called "Setting up Your Workspace on Windows" and "Setting Up Your Workspace on Mac" will demonstrate this process, so you can wait until then.

Set up your course workspace

Right now, you should create a version-control directory (a more computer-science-y term for “folder”) to hold all your files for this course in an easy to remember location, then create a reflections sub-directory, and within that, create a plain text file called lesson_1_reflections.txt for the questions from this lesson.

You can do this by running the following commands in either Git Bash or the terminal (the bits after the # signs are comments, anything after those are not interpreted):

cd ~                          # change directories to your home directory
mkdir version-control         # make version-control directory
cd version-control            # go to version-control directory
mkdir reflections             # create reflections directory
cd reflections                # go to reflections directory
subl lesson_1_reflections.txt # launch sublime with file called lesson_1_reflections.txt (you can replace subl with another editor here if you prefer a different one)

pwd # print working directory - shows what directory you are in
ls  # list the files in this directory

http://www.git-tower.com/blog/git-cheat-sheet/
git clone to clone existing repository
git init to make a new one (must be in the folder you want to set git for)

https://try.github.io/levels/1/challenges/1

http://gitimmersion.com/










