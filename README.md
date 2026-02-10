# JenkinsJava


simmaco@simmaco-2 JenkinsJava % git init
Reinitialized existing Git repository in /Users/simmaco/Projects/Infrastructure/JENKINS/JenkinsJava/.git/

simmaco@simmaco-2 JenkinsJava % git config user.name simmaco.devel
simmaco@simmaco-2 JenkinsJava % git config user.email simmaco.devel@gmail.com
simmaco@simmaco-2 JenkinsJava % git config --list
credential.helper=osxkeychain
init.defaultbranch=main
user.name=simmaco
user.email=simmaco.marandino@warda.it
core.autocrlf=input
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
branch.main.gk-last-accessed=2026-02-10T09:08:01.676Z
user.name=simmaco.devel
user.email=simmaco.devel@gmail.com

simmaco@simmaco-2 JenkinsJava % git add README.md
git commit -m "first commit"
git branch -M main
[main (root-commit) edeaa58] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md


simmaco@simmaco-2 JenkinsJava % git remote add origin git@github.com:simmacodevel/JenkinsJava.git

simmaco@simmaco-2 JenkinsJava % git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:simmacodevel/JenkinsJava.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
