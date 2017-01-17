# usefulShellCMDs

WGET useful commands

# Downloads the files recursively and removes the index file
wget -r -nH -nd -np --reject "index.html*" <URL>

GIT Commands

#-lists log in requested format
git log --pretty=format:"%h - %an, %ar : %s"

#-lists in format of liking within the mentioned time
git log --since=1.hour --pretty=format:"%h - %an, %ar : %s"
