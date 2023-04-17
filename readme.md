[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]

<div align="center">
  <a href="#">
    <img src="https://thumbs.gfycat.com/AbsoluteHealthyAyeaye-max-1mb.gif" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">Inteligência Artificial e Machine Learning</h3>
  <p align="center">Primeira Atividade Avaliativa</p>

</div>

## 🔰 Começando

Esse projeto foi criado para realizar um processo de ETL direto para uma base de dados MySQL, implementado na linguagem Python.

<br/>

### 💾 Suporte de primeiro-nível

[![vscode][vscode]][vscode-url]

### 🤖 Tecnologias empregadas

[![Python][Python]][Python-url]

### 📋 Pré-requisitos

- 🐋Docker
- 🐍Python
  - Pandas
  - PyMySQL
  - SQLAlchemy

>💡Atenção
>
> Existe um arquivo ```requirements.txt```, onde todas as dependências estão listadas. Basta executar o script ```install_requirements.bat``` para instalar as dependências listadas no arquivo.

<br/>

## 🎨 Funcionalidades
A aplicação conta com a seguinte funcionalidade:

<br/>

### 🛠️ Processo de ETL para a base de dados

O processo irá carregar o arquivo em um dataframe, fazendo inferencia automatica (essa configuração consome MUITA RAM) de todas as colunas.
Será feita uma conexão ao servidor de base de dados levantado pelo container docker, que está configurado no projeto e, então, criada uma base de dados "pnad" para que a tabela "pnad_2019_3" seja escrita.

O processo demora cerca de 25 minutos.

<br/>

## 📑 Licenças

Distribuído sob a MIT License. Veja `LICENSE` para mais informações.

<!-- ASSETS -->

<!-- BADGE - Contributors -->

[contributors-shield]: https://img.shields.io/github/contributors/toledkrw/IA_ML-Trabalho_1.svg?style=for-the-badge
[contributors-url]: https://github.com/toledkrw/IA_ML-Trabalho_1/graphs/contributors

<!-- BADGE - Issues -->

[issues-shield]: https://img.shields.io/github/issues/toledkrw/IA_ML-Trabalho_1.svg?style=for-the-badge
[issues-url]: https://github.com/toledkrw/IA_ML-Trabalho_1/issues

<!-- BADGE - License -->

[license-shield]: https://img.shields.io/github/license/toledkrw/IA_ML-Trabalho_1.svg?style=for-the-badge
[license-url]: https://github.com/toledkrw/IA_ML-Trabalho_1/blob/main/LICENSE

<!--  -->
<!-- TECHNOLOGIES -->
<!--  -->

<!-- BADGE - Python -->

[Python]: https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/

<!-- BADGE - vscode -->

[vscode]: https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white
[vscode-url]: https://code.visualstudio.com/
