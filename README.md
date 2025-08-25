# Automação de Downloads com Selenium
Automação em Python criada para simplificar e agilizar o download de arquivos no eSocial, utilizando Selenium para eliminar tarefas repetitivas e garantir maior eficiência e precisão no processo.

### Sobre o Projeto

Este projeto foi criado para **simplificar e agilizar o processo de download** de arquivos no eSocial utilizando o Selenium. Ele foi configurado para navegar automaticamente pelo sistema, baixar e direcionar os arquivos de forma programática.

**⚠️ Observação:** O login é realizado manualmente, pois o eSocial possui mecanismos de detecção de automação. Após o login, o processo é executado automaticamente, eliminando a necessidade de intervenção repetitiva e garantindo maior eficiência e precisão, o que o torna ideal para tarefas rotineiras.

---
### ⚙️ Funcionalidades
---
- Realiza o login manualmente (usuário entra com suas credenciais, devido à detecção de automação do eSocial).
- Navega automaticamente até a seção de downloads.
- Faz o download dos arquivos de forma programática.
- Direciona os arquivos para a pasta pré-definida.
- Elimina a necessidade de repetição manual, garantindo mais agilidade e precisão.
---
### 💻 Tecnologias Utilizadas
---
- Vscode
- Python 3.13.9
- Selenium
- Undetected-chromedriver
- Openpyxl
---
### Instalações
---
Para rodar este script, certifique-se de que o Python e as bibliotecas necessárias estão instalados em sua máquina. Caso não tenha nada instalado, deixarei o link para o download do Python, além do comando para instalar as dependências diretamente pelo terminal do VS Code.

## Instalação do Vscode
### Passo 1°: Acessar o site oficial.
Para começar a instalação, clique no link abaixo:

[📥 Download - Vscode](https://code.visualstudio.com/)

Na página de download, clique na versão adequada para o seu sistema operacional (Windows, macOS ou Linux). Em seguida, execute o arquivo baixado e siga as instruções do instalador.

## Instalação do Python

### Passo 1°: Acessar o site oficial.
Para fazer a instalação, basta voce clicar no link abaixo:

[📥 Download - Python](https://www.python.org/downloads/)

Clique em Downloads → Windows (o site geralmente já sugere a versão correta para o seu sistema).

**⚠️ Observação:** É necessário utilizar o Python na versão 3.10 ou superior. O projeto foi testado na versão 3.13.9, portanto versões anteriores podem não funcionar corretamente.

### Passo 2°: Baixar o instalador.
Clique em Download Python 3.xx.x (a versão mais recente, por exemplo, 3.13.9).

Salve o arquivo ```.exe```no seu computador.

### Passo 3°: Executar o instalador

Clique duas vezes no arquivo ```.exe``` baixado.

Clique em ```Install Now``` e aguarde a instalação terminar.

### Passo 4°: Verificar a instalação

Abra o Prompt de Comando (pressione ```Win + R```, digite ```cmd``` e pressione Enter).

Digite:

```
python --version
```
ou
```
py --version
```
Se aparecer a versão do Python que você instalou, tudo certo!

## Instalação das bibliotecas 

Abra o seu terminal e digite os comandos para instalar as bibliotecas necessárias:
```
pip install Selenium
pip install undetected-chromedriver
pip install openpyxl
 ```

## Como executar

Abra o seu terminal no diretorio do projeto e digite:
```
python main.py
```

## Estrutura do Projeto
O projeto está organizado da seguinte forma:
```
├── Automação - esocial/
|   ├── EFETIVO - EXEMPLO.xlsX   # Arquivo de dados de exemplo.
|   ├── LICENSE                  # Licença do projeto.
|   ├── main.py                  # O script principal de automação.
|   ├── README.md                # Este arquivo de documentação.
|   └── requeriments.txt         # Dependências do projeto.
```









