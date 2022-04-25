# tag-testing
tag-testing .......................
feature/2


To sum up if your remote is called origin and you're working on master branch:

git tag -d <tagname>                  # delete the old tag locally
git push origin :refs/tags/<tagname>  # delete the old tag remotely
git tag <tagname> <commitId>          # make a new tag locally
git push origin <tagname>             # push the new local tag to the remote 

Description:

    Line 1 removes the tag in local env.
    Line 2 removes the tag in remote env.
    Line 3 adds the tag to different commit
    Line 4 pushes the change to the remote
