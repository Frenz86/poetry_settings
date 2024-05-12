# poetry_settings

## 1 install pipx:
py -m pip install --user pipx

## 2 add pipx to path:
cd C:\Users\Frenz\AppData\Roaming\Python\Python311\Scripts
.\pipx.exe ensurepath

## 3 install poetry with pipx:
pipx install poetry

## 4 create new projet with poetry
poetry new appfast --name src

## 5 .venv 
poetry shell





poetry run uvicorn src.main:app
