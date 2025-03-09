
 # Projeto atv0006
### Projeto: Informações sobre o Continente Americano

Este projeto tem como objetivo fornecer informações detalhadas sobre o continente americano, incluindo dados populacionais, indicadores socioeconômicos e rankings relacionados a países e cidades. O sistema é composto por uma página inicial e quatro páginas adicionais, cada uma com um foco específico.

## Funcionalidades do Projeto

### **Página Inicial**
- Boas-vindas ao usuário.
- Descrição do sistema e suas funcionalidades.

### **Lista de Países por Região**
- Lista de todos os países do continente americano, separados por região:
  - América do Norte
  - América Central
  - América do Sul

### **Populações e Cidades Mais Populosas**
- População total de cada região (América do Norte, Central e Sul).
- Cidade mais populosa de cada região e seu valor populacional.

### **Ranking de IDH e Renda Per Capita**
- Os 5 países com maior IDH (Índice de Desenvolvimento Humano) e seus valores.
- Os 5 países com maior Renda Per Capita e seus valores.

### **Ranking de Médias Salariais em TI**
- Ranking dos países com as maiores médias salariais em Tecnologia da Informação (TI), com base nos dados fornecidos.

### **Tecnologias Utilizadas**
* Front-end:
  - HTML5
  - CSS3 


### **Ferramentas de Desenvolvimento:**
  - Git e GitHub 
  - Visual Studio Code 

### **Fontes de Dados:**

Dados populacionais e socioeconômicos: [IBGE](https://www.ibge.gov.br/).

Dados salariais em TI: [Planilha de Dados](https://docs.google.com/spreadsheets/d/1BDCCAlw4mcZHNO2OnWPq33rJNXPGd9IY_MdeTHbYN44/edit?gid=0#gid=0)

## Fluxo de Trabalho com Git e GitHub
### **Criação do Repositório:**
1. Criar um repositório no GitHub para o projeto
* Repositório `atv0006` criado.
* Adicionada a descrição do projeto.
* Adicionado o arquivo `README.md `com informações iniciais.
* Adicionado o arquivo `.gitignore` para excluir arquivos desnecessários no versionamento.
* Definida a licença MIT, permitindo uso aberto do código.
### **Criação do Projeto**
Criado o projeto `atv0006` no GitHub Projects para organizar e gerenciar as Issues e Pull Requests, facilitando o acompanhamento do desenvolvimento e a colaboração da equipe.
### **Criação da Issue**
Criada a Issue `#1 - Desenvolvimento da Página Inicial` para registrar a
tarefa de desenvolvimento das páginas do projeto.
### **Clone Repositório local**
1. Clone o repositório localmente:
 ```bash
   git clone https://github.com/Daniela2319/atv0006.git
   ```

### **Branchs:**
* Foram criadas as branches dev e homolog para os ambientes de desenvolvimento e homologação, além de branches separadas para cada nova funcionalidade ou página da aplicação. Dessa forma, as alterações são organizadas e testadas antes de serem integradas à branch principal de produção.

```
git checkout -b feature/nome-da-funcionalidade
```
### **Commits:**
* Faça commits frequentes com mensagens descritivas:
```
git add .
git commit -m "Adiciona página inicial com boas-vindas"
```
### **Pull Requests (PRs)**
* Abrir um Pull Request para revisão e integração das alterações, seguindo o fluxo: primeiro para a branch dev, depois para homolog e, por fim, para main após validação.

## **Estrutura do Projeto**

```
├── index.html                      # Página inicial
├── styles.css                        # Arquivo css estilização
├── HTML                            # Pasta das páginas 
│   ├── paises.html               # Lista de países por região
│   ├── populacoes.html       # Populações
│   ├── idh-renda.html         # Ranking de IDH e Renda Per Capita
│   ├── salarios-ti.html        # Ranking de médias salariais em TI
└── README.md               # Documentação do projeto
```   

## **Licença**
Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). 

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

## **Contato**
Em caso de dúvidas ou sugestões, entre em contato:

**Nome:**  Daniela Velter

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/danielavelteredu/)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/Daniela2319)

