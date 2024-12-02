https://aichatbot1998.streamlit.app/

echo "# AI_chatbot" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/ByungwookYang/AI_chatbot.git

git push -u origin main

conda env create -f environment.yml


conda activate thyroid_cancer_chatbot


conda deactivate


conda env remove --name thyroid_cancer_chatbot
