# Flashcards
Find and update vocubulary txt's (which are consistent with Quizlet's import conventions) and jsons in the `vocab` folder.\
Run `normalize.ipynb` to ensure consistentency between a given vocabulary json and vocabulary txt.\
Run `main.ipynb` on your desired json path to create a new flashcards pdf in the `flashcards` folder.

# Setup
Move to your desired directory for this repo, then...
```
git clone https://github.com/PeterFavero/Flashcards.git
cd Flashcards
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```
...and set `.venv` as the kernel in `main.ipynb`.
