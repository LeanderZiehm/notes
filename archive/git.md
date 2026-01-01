
# Rename branch
git branch -m language-learning-game-backend language-learning-game-backup-v0
git push origin -u language-learning-game-backup-v0
git push origin --delete language-learning-game-backend
git fetch -p


