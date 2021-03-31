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
	- Pré-processamento
4. Modelação
	- Escolher modelo *baseline*
	- Definir e processar *features*
	- Separação em dados de treino e teste
	- Implementar processos de treino e teste
	- Implementar testes
	- Treinar modelo

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

- **data**: dados em bruto e dados processados
- **models**: modelos treinados
- **notebooks**: *notebooks* do *Jupyter* para análise e visualizações
- **outputs**: imagens, gráficos e outros ficheiros que sejam gerados e não sejam código
- **scripts**: *scripts* de **processos**
- **src**: código
- **tests**: testes unitários, de integração, de dados e de modelo
- **venv**: *virtual environment*
- **LICENSE**: licença de *software*
- **README.md**: descrição do projeto e outras informações
- **requirements-essential.txt**: requisitos mínimos para correr o projecto
- **requirements-complete.txt**: requisitos completos para correr o projecto e garantir reprodutibilidade
