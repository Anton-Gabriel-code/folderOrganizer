# 📂 File Organizer (Python)
Um script simples em Python para organizar automaticamente sua pasta de Downloads (ou qualquer outra pasta) movendo os arquivos para subpastas baseadas em suas extensões (ex: .pdf, .png, .docx).

## Como funciona?
O script percorre todos os arquivos de um diretório específico, identifica a extensão de cada um e:

> Verifica se já existe uma pasta com o nome daquela extensão.
> 
> Se não existir, ele cria a pasta automaticamente.
> 
> Move o arquivo para dentro da respectiva pasta.

## 🛠️ Tecnologias Utilizadas
> Python 3
>
> Biblioteca os: Para manipulação de caminhos e diretórios.
>
> Biblioteca shutil: Para mover os arquivos.

## Pré-Requisitos?
> Ter o Python3 instalado na sua máquina

## 🔧 Como usar
> Clone este repositório ou baixe o arquivo folder_organizer.py.
>
> Certifique-se de que o caminho no código (.replace(...)) aponta corretamente para a pasta que você deseja organizar.
>
> Abra o terminal na pasta do projeto e execute:
    python3 folder_organize.py


