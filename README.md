# APO
# Programação em Python

Este repositório é um compilado das aulas do curso de Data Science da PUCRS. Professores (Felipe Meneguzzi e Henry Cagnini)

Alterações podem ser realizadas devido ao andamento das aulas.

## Visualização local 

### Criação do ambiente virtual 
Para visualizar os slides, é necessário criar um ambiente virtual no Anaconda:

1. Instale a distribuição Anaconda do Python 3: [link](https://www.anaconda.com/download/#linux)
2. Crie um novo interpretador Python:

```
conda create --name py3 python=3
```
3. Ative o ambiente virtual 

no Linux:
```
source activate py3
```
no Windows:
```
activate py3
```

4. Instale os pacotes necessários usando o arquivo ```requirements.txt```:

```
conda install --file requirements.txt
```

### Visualização dos notebooks (sem html)

1. Ative o ambiente virtual 

no Linux:
```
source activate py3
```
no Windows:
```
activate py3
```
2. Ative o jupyter notebook:

```
jupyter notebook
```

3. Dentro da interface aberta, navegue até a pasta onde o notebook está e abra-o.

### Visualização dos notebooks (em html)

Para gerar slides de contedo das aulas, utilize o seguinte comando (na linha de comando):

```
jupyter nbconvert python_avancado/classes_01_construtores.ipynb --to slides --post serve
```

Isto gerará um arquivo .html na **mesma pasta em que o notebook está**, e abrirá uma nova janela no navegador padrão, com a apresentação de slides. Para sair da apresentação, simplesmente feche a janela no navegador e termine o processo no terminal utilizado para invocar o comando.

**Note que este comando deve sempre ser utilizado para realizar a apresentação de slides. Abrir o arquivo .html não habilitará o modo de apresentação.**

### Comandos Basicos clone, commit e push (junto ao GIT)
** Ir até o diretório que se pretende clonar ou commitar.

CLONE:
```
git clone local.git
```
COMMIT:
```
git commit -m local.git .
```
PUSH:
```
git clone local
```
