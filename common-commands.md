`
init
git remote add <myRemoteName> <theRemoteUrl>

status
diff
branch [-all]
log [--graph]
remote --verbose

add --all
commit --message="My Comment"
push [--all --set-upstream <myRemoteName>]

fetch --all <theBranchName> 
branch <newBranchName> 
checkout <currentBranchName>
merge <otherBranchName>

reset --hard <commitID>
clean -xdf
`