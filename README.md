# 🐾 VetCare+

Sistema de gerenciamento para clínicas veterinárias desenvolvido como projeto da disciplina **Projeto de Software**.

## 📚 Sobre o Projeto

O VetCare+ é um projeto acadêmico desenvolvido para a disciplina de Projeto de Software, com o objetivo de aplicar conceitos de análise e modelagem orientada a objetos por meio da documentação completa de um sistema de gestão para clínicas veterinárias.

O trabalho contempla a especificação dos requisitos, modelagem UML, arquitetura de software, modelagem de dados e documentação técnica do sistema, sem a implementação do código-fonte da aplicação.

A maior parte dos diagramas foi desenvolvida utilizando PlantUML. Os diagramas de comunicação foram elaborados no Canva para melhor representação visual. Os arquivos-fonte PlantUML encontram-se na pasta `Codigo_PlantUML`.

## 📄 Documentação

A documentação completa do projeto encontra-se no arquivo:

`Documentacao_Projeto_VetCarePlus.pdf`

Nesse documento estão descritos:

* Introdução ao sistema;
* Atores e requisitos funcionais;
* Casos de uso;
* Contratos de operação;
* Arquitetura do sistema;
* Diagramas UML;
* Modelo de dados;
* Decisões de projeto adotadas durante a modelagem.

## ✨ Funcionalidades Principais

* 🔐 Autenticação de usuários.
* 👤 Cadastro de clientes.
* 🐶 Cadastro de animais.
* 📅 Agendamento de consultas.
* 🩺 Registro de atendimentos veterinários.
* 💉 Registro de vacinação.
* 📄 Emissão de receitas veterinárias.
* 📚 Consulta de histórico médico.
* 📊 Geração de relatórios administrativos.

## 🛠 Tecnologias Utilizadas

### Modelagem e Documentação

* UML (Unified Modeling Language)
* PlantUML
* GitHub
* Canva

## 🏗 Arquitetura

Foi proposta uma arquitetura em camadas para o sistema, composta por:

- Camada de Apresentação
- Camada de Negócio
- Camada de Persistência

A arquitetura foi definida durante a etapa de projeto com o objetivo de organizar as responsabilidades do sistema e facilitar futuras implementações.

## 📂 Estrutura do Repositório

```text
Documentacao-de-projeto-VetCare/

├── Codigo_PlantUML/
│   ├── Arquitetura.puml
│   ├── Diagrama_de_Casos_de_Uso.puml
│   ├── Diagrama_de_Classes.puml
│   ├── Diagrama_de_Componentes.puml
│   ├── Diagrama_de_Estados.puml
│   ├── Diagrama_de_Implantacao.puml
│   ├── Modelo_de_Dados.puml
│   │
│   ├── Diagramas_de_Sequencia/
│   │   ├── DS-01_Agendar_Consulta.puml
│   │   ├── DS-02_Registrar_Atendimento.puml
│   │   └── DS-03_Registrar_Vacinacao.puml
│   └── 
│
├── Diagramas/
│   ├── Arquitetura.png
│   ├── Casos de Uso.png
│   ├── Diagrama de Classes.jpeg
│   ├── Diagrama de Componentes.png
│   ├── Diagrama de Estados.png
│   ├── Diagrama de Implantacao.png
│   ├── Modelo de Dados.png
│   │
│   ├── Diagramas_de_Sequencia/
│   │   ├── DS-01_Agendar_Consulta.png
│   │   ├── DS-02_Registrar_Atendimento.png
│   │   └── DS-03_Registrar_Vacinacao.png
│   │
│   └── Diagramas_de_Comunicacao/
│       ├── DC-01_Agendar_Consulta.png
│       ├── DC-02_Registrar_Atendimento.png
│       └── DC-03_Registrar_Vacinacao.png
│
├── Documentacao_Projeto_VetCarePlus.pdf
│
└── README.md
```


## 📑 Diagramas Desenvolvidos

O projeto contém os seguintes artefatos de modelagem:

### Diagramas Estruturais

- Diagrama de Classes
- Diagrama de Componentes
- Modelo Entidade-Relacionamento (DER)

### Diagramas Comportamentais

- Diagrama de Casos de Uso
- Diagrama de Estados

### Diagramas de Interação

#### Diagramas de Sequência

- DS-01 — Agendar Consulta
- DS-02 — Registrar Atendimento
- DS-03 — Registrar Vacinação

#### Diagramas de Comunicação

- DC-01 — Agendar Consulta
- DC-02 — Registrar Atendimento
- DC-03 — Registrar Vacinação

### Diagramas Arquiteturais

- Arquitetura do Sistema
- Diagrama de Implantação

Todos os diagramas foram desenvolvidos utilizando PlantUML, exceto os de Comunicação, feitos no Canva, seus respectivos códigos-fonte encontram-se na pasta `Codigo_PlantUML`.

## 👤 Autora

**Giovanna Lima Torres Guasch**

Projeto desenvolvido individualmente para a disciplina de Projeto de Software.

## 📄 Licença

Este projeto possui finalidade exclusivamente acadêmica.
