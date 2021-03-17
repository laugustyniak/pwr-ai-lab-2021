# Instalacja python'a 

## Conda

### Instalacja 

[https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)

### Stworzenie środowiska 

`conda create --name pwr-ai-lab python=3.7 -y`

Po stworzeniu wirtualnego środowiska aktywujemy je

`conda activate pwr-ai-lab`


## Instalacja wymaganych biblioteki do list zadań 

`pip install -r requirements.txt`

Po ich zainstalowaniu możesz uruchomić jupyter notebooka poprzez 

`jupyter notebook --NotebookApp.token='' --NotebookApp.password=''`

W ten sposób nie będzie potrzebować ani hasła ani tokenu do włączenia notebooka.
 