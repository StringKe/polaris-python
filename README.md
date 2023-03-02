# polarismesh

[![PyPI - Version](https://img.shields.io/pypi/v/polarismesh.svg)](https://pypi.org/project/polarismesh)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/polarismesh.svg)](https://pypi.org/project/polarismesh)

-----

**Table of Contents**

- [Installation](#Installation)
- [Usage](#Usage)
- [Development](#Development)

## Installation

python version >= 3.7 (grpc requires python >= 3.7)

```console
pip install polarismesh
```

## Usage

```python

```

## Development

1. please install [conda](https://docs.conda.io/en/latest/miniconda.html) first.
2. create a conda environment with python 3.9
   ```
    conda create -n polarismesh python=3.9
   ```
3. activate the environment
   ```
    conda activate polarismesh
   ```

### Auto activate conda environment

add the following to your `~/.bashrc` or `~/.zshrc` file

```bash
# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/opt/homebrew/anaconda3/bin/conda' 'shell.zsh' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/opt/homebrew/anaconda3/etc/profile.d/conda.sh" ]; then
        . "/opt/homebrew/anaconda3/etc/profile.d/conda.sh"
    else
        export PATH="/opt/homebrew/anaconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<

# >>> conda auto active >>>
if [[ -f .conda ]]; then
    conda activate $(cat .conda)
elif [[ -f .miniconda ]]; then
    conda activate $(cat .miniconda)
fi
# <<< conda auto active <<<
```