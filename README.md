# Passos de um projecto de data science:
##### Baseado no guia de [Mihail Eric](https://www.mihaileric.com/posts/setting-up-a-machine-learning-project/)

1. Definir o problema
	- O que quero saber?
 	- O que quero resolver?
 	- Como vou decidir se está feito?
2. Organizar pasta/repositório
	- [Estrutura de pastas](#estrutura-de-pastas)
	- git
	- .gitignore
	- Licença
	- README.md
	- requirements-essential.txt
	- requirements-complete.txt
3. Dados
	- Recolher os dados que se pensa que possam ser úteis para abordar o problema definido no ponto 1
	- Análise exploratória
	- Limpeza

### Estrutura de pastas
```
project_name/
  data/
    raw/
    processed/
  models/
  notebooks/
  outputs/
  scripts/
  src/
  tests/
  venv/
  LICENSE
  README.md
  requirements-essential.txt
  requirements-complete.txt
```

- **data**: dataset(s) in its raw and processed forms
- **models**: trained models
- **notebooks**: Jupyter notebooks for analysis
- **outputs**: images, plots and other non-source files generated
- **scripts**: one-off scripts for *processes*
- **src**: source code
- **tests**: unit/integration/data/model tests
- **venv**: virtual environment
- **LICENSE**: software license
- **README.md**: project description and other information
- **requirements-essential.txt**: minimal requirements for running the project
- **requirements-complete.txt**: complete requirements for running the project to ensure reproducibility
