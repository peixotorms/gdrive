# Readme
A shell script to download large files from google drive directly from the command line

# How to use?

1. Get a shareable link from your google drive, like: `https://drive.google.com/open?id=XXXXXXXXXXXXXXXXXXXX`
2. CD to the working directory and run:

`curl -L https://goo.gl/CvHjqx | bash -s "https://drive.google.com/open?id=XXXXXXXXXXXXXXXXXXXXX"`
