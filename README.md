git clone https://github.com/pyenv/pyenv.git .pyenv
export PYENV_ROOT=.pyenv
.pyenv/bin/pyenv install
eval "$(.pyenv/bin/pyenv init -)"
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt