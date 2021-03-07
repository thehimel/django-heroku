# Note

## Install Miniconda in Linux

- Go to: [this link](https://docs.conda.io/en/latest/miniconda.html)
- Download the .sh file from the list for Linux.

- Make it executable:
`chmod +x filename.sh`

- Run the file:
`./filename.sh`

- Set the environment variable:
`export PATH=~/anaconda3/bin:$PATH`

- Check the installation:
`conda --version`

## Create Virtual Environment with Miniconda

```sh
conda create --name djh python=3.7
conda activate djh
pip install -r requirements.txt
pip freeze > requirements.txt

pip install django
```
