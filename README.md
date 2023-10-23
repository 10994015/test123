## 下載 KDiff3
網址:https://sourceforge.net/projects/kdiff3/

#### 輸入指令
git config --edit --global

#### .gitconfig
[user]
	name = 10994015
	email = a0938599191@gmail.com
[meger]
	tool = kdiff3
[mergertool]
	prompt = false
	keepBackup = false
	keepTemporaries = false
[mergertool "kdiff3"]
	cmd = kdiff3 "$BASE" "$LOCAL" "$REMOTE" -o "$MERGED"
	trustExitCode = true
