git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ByungwookYang/-.git
git push -u origin main

conda env create -f environment.yml


conda activate thyroid_cancer_chatbot


conda deactivate


conda env remove --name thyroid_cancer_chatbot
