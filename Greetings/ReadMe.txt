This is the Git Inside Out 3rd session Files.

echo "Welcome To Git Inside Out Session!" | git Hash-Object --stdin (In Memmory)

echo "Welcome To Git Inside Out Session!" | git Hash-Object --stdin -w (To Write In Disk)

git cat-file {SHA-1 key} -p (Pretty Print)
git cat-file {SHA-1 key} -t  (Type of the content)
git status

git branch 			:(Displays the list of branches)
git branch {branch-name} 	:(Creates new branch)
git commit -m "{your-comments-related to commit}" 
.............................................................................................
this is master's commit to create the conflicts with new-read me branch
------------------------------------------------------------------------------------------------------------------
some contents in read-me to create conflicts
