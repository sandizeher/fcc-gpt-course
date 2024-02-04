# fcc-gpt-course

## set environent
- sudo apt install python3.10-venv
- python3.10 -m venv fcc-cuda
- activate

## libraries
- pip3 install matplotlib numpy pylzma ipykernel jupyter
- pip3 install torch --index-url https://download.pytorch.org/whl/cu118

## open jupyter notebook from bash
- jupyter notebook

## setup kernel in jupyter notebook
- python3 -m ipykernel install --user --name=fcc-no-cuda