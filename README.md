"# heart-disease-prediction-xai" 
## 👥 Collaborating on this Project

### Clone the Repo
In anaconda prompt/terminal

git clone https://github.com/sanjay2721/heart-disease-prediction-xai.git

cd heart-disease-prediction-xai
## Set Up the Environment
conda env create -f environment.yml

conda activate xai_env

## Work on the Project
Use notebooks/ for Jupyter notebooks

Add scripts in src/

Save models in models/

Add reports in reports/

# If a teammate only has requirements.txt, and no environment.yml, they can still set up the project like this:
 Setup Using requirements.txt (with Anaconda):
conda create --name xai_env python=3.11

conda activate xai_env

pip install -r requirements.txt


# How to Collaborate Using Git
Basic Git workflow for each teammate:

✅ Pull latest changes:

bash

git pull origin main

✅ Add and commit changes:

bash

git add .

git commit -m "Your message here"

✅ Push to GitHub:

bash

git push origin main

🔁 Repeat this workflow whenever changes are made.
