✅ 1. Unique libraries used in your code

From your code, you only need to worry about installing:

pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
🔹 ✅ 2. Installation commands (IMPORTANT)

👉 Use this single command to install everything:

pip install pandas numpy matplotlib seaborn scikit-learn nltk

✔️ This is enough in most cases
✔️ Works in terminal / command prompt / Jupyter (!pip)

🔹 ✅ 3. If using Jupyter Notebook

Use:

!pip install pandas numpy matplotlib seaborn scikit-learn nltk
🔹 ✅ 4. NLTK downloads (VERY IMPORTANT)

Even after installing nltk, you must download datasets:

import nltk

nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
nltk.download('wordnet')

👉 ⚠️ Important:

❌ punkt_tab → NOT required
❌ averaged_perceptron_tagger_eng → NOT required

✔️ Only use the 4 above

🔹 ✅ 5. Clean import version (for exam)

Use this clean version (no repetition):

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import confusion_matrix, accuracy_score, classification_report

import nltk
🔹 🚨 6. What if installation is not allowed?

In college labs:

👉 Usually libraries are pre-installed

If not:

Use:
pip install <library_name>

Example:

pip install pandas
🔹 ⚡ 7. Quick emergency checklist (before practical)

✔️ Run this once:

import pandas, numpy, matplotlib, seaborn, sklearn, nltk

If no error → you're safe ✅

🔥 Final Answer (what to remember)

👉 Single command:

pip install pandas numpy matplotlib seaborn scikit-learn nltk

👉 NLTK setup:

nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
nltk.download('wordnet')
🚀 Pro tip (exam saver)

If internet is slow or blocked:

Skip install

Write code + mention:

“Required libraries should be pre-installed”












🧠 Core libraries (you already have ✅)

These are must-have:

pip install pandas numpy matplotlib seaborn scikit-learn nltk
🔹 ⚠️ Extra libraries (just in case)
1) Jupyter Notebook (if you’re not given one)
pip install notebook

👉 Needed if you run .ipynb files

2) SciPy (sometimes required by sklearn)
pip install scipy

👉 Some ML functions depend on it

3) joblib (used internally by sklearn)
pip install joblib

👉 Usually auto-installed, but good fallback

4) regex (for NLP sometimes)
pip install regex

👉 Rare, but used in text processing

5) tqdm (for progress bars – optional)
pip install tqdm

👉 Not required, but sometimes used

🔹 🔥 ONE SAFE COMMAND (covers everything)

If you want a single “no risk” command:

pip install pandas numpy matplotlib seaborn scikit-learn nltk scipy notebook joblib

👉 This is your ultimate backup command

🔹 ⚠️ NLTK (MOST COMMON PROBLEM IN EXAMS)

Even if installed, downloads may be missing:

import nltk

nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
nltk.download('wordnet')

nltk.download('omw-1.4')  # optional safety

Not Required but might require:
nltk.download('punkt_tab')                      ❌
nltk.download('averaged_perceptron_tagger_eng') ❌

Optonal(Very rare in exam)
nltk.download('maxent_ne_chunker')
nltk.download('words')

Advanced:
nltk.download('brown')       # corpus
nltk.download('gutenberg')   # books dataset
nltk.download('reuters')     # news dataset

👉 THIS is the #1 thing students forget

🔹 🚨 Worst-case scenarios (real exam issues)
❌ No internet
You cannot install anything

Solution:
👉 Write code + mention:

“Libraries assumed pre-installed”

❌ pip not working

Try:

python -m pip install pandas
❌ Permission error
pip install --user pandas
🔹 ⚡ Ultra-quick checklist before exam

Run this:

import pandas
import numpy
import matplotlib
import seaborn
import sklearn
import nltk

If no error → YOU ARE SAFE ✅

🔥 Final answer (what to remember)

👉 Minimum:

pip install pandas numpy matplotlib seaborn scikit-learn nltk

👉 Worst-case safe:

pip install pandas numpy matplotlib seaborn scikit-learn nltk scipy notebook joblib
🚀 Honest advice (important)

Don’t try to memorize 20 installs.
👉 Just remember one big command + NLTK downloads.