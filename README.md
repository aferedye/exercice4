# Exercice 4 de github  
******************************  
  
Séquence d'introduction :  
  
1 :  
git commit -m "first commit"  
git commit -m "second commit"  
  
2 :  
git checkout -b bugFix  
  
3 :  
git checkout -b bugFix  
git commit  
git checkout main  
git commit  
git merge bugFix  
  
4 :  
git checkout -b bugFix  
git commit  
git checkout main  
git commit  
git checkout bugFix  
git rebase main  
  
Montée en puissance :  
  
1 :  
git checkout C4  
  
2 :  
git checkout bugFix^  
  
3 :  
git branch -f bugFix HEAD~2  
git checkout HEAD^  
git branch -f main C6  
  
4 :  
git checkout local  
git reset C1  
git checkout pushed  
git revert C2  
  
Déplacer le travail :  
  
1 :  


