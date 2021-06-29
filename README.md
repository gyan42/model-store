# model-store
Model store for custom build DL models

```
sudo apt install git-lfs

git-lfs install
git-lfs track "*.mar"
git add .gitattributes
git status

git add bertv1.mar
git commit -m "HF bert model trained on conll2003 dataset"
git push origin HEAD
```
