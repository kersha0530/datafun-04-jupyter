# datafun-04-jupyter
echo "# datafun-04-jupyter" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kersha0530/datafun-04-jupyter.git
git push -u origin main
git remote add origin https://github.com/kersha0530/datafun-04-jupyter.git
git branch -M main
git push -u origin main
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install jupyterlab pandas matplotlib seaborn
py -m pip freeze > requirements.txt
