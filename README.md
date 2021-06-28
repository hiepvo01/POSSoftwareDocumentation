## Create Environment and Install packages

python -m venv .venv

.venv/Scripts/activate

pip install -r requirements.txt

## To Start from saved notebook

import dill

dill.load_session('notebook_env.db')

df.head()