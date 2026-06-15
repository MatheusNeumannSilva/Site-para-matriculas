<div align="center">

# Estrelas do Amanhã

Formulário de matrícula escolar desenvolvido com HTML e CSS, com foco em uma interface clara, organizada e visualmente fiel a um fluxo real de inscrição.

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-f3541c?style=for-the-badge)](#)
[![HTML](https://img.shields.io/badge/HTML5-estrutura-e34f26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS3-estilos-1572b6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-publicado-222?style=for-the-badge&logo=github&logoColor=white)](https://matheusneumannsilva.github.io/Site-para-matriculas/)

[Acessar projeto](https://matheusneumannsilva.github.io/Site-para-matriculas/) ·
[Ver repositório](https://github.com/MatheusNeumannSilva/Site-para-matriculas)

</div>

---

## Sobre o projeto

O **Estrelas do Amanhã** é uma página de formulário para matrícula infantil. O projeto simula uma experiência de inscrição escolar, reunindo campos de dados da criança, endereço, responsável legal, opções de turno, esportes, upload de documento e aceite de termos.

A proposta principal é praticar a construção de formulários com HTML semântico e CSS modular, mantendo a interface organizada, responsiva e próxima de um layout profissional.

## Funcionalidades

- Formulário de matrícula com campos organizados por seções.
- Coleta de informações da criança.
- Campo de data de nascimento.
- Seleção de sexo.
- Área para informações médicas.
- Upload de certidão de nascimento.
- Campos de endereço residencial.
- Campos de contato do responsável.
- Validação visual para e-mail obrigatório.
- Seleção de turno de estudo.
- Seleção de esporte com radio cards personalizados.
- Checkbox de aceite dos termos e política de privacidade.
- Botões de ação para salvar respostas e enviar matrícula.

## Tecnologias utilizadas

- **HTML5** para a estrutura da página.
- **CSS3** para estilização, layout e estados visuais.
- **SVG assets** para ícones e ilustração.
- **GitHub Pages** para publicação.

O projeto não usa JavaScript, frameworks ou etapa de build. Isso torna a página simples de executar, estudar e versionar.

## Estrutura de pastas

```text
Site-para-matriculas/
├── assets/
│   ├── Illustration.svg
│   └── icons/
├── styles/
│   ├── fields/
│   │   ├── buttons.css
│   │   ├── checkbox.css
│   │   ├── droparea.css
│   │   ├── index.css
│   │   ├── input.css
│   │   └── radio.css
│   ├── forms.css
│   ├── global.css
│   ├── index.css
│   └── layout.css
├── index.html
└── README.md
```

## Como executar localmente

Você pode abrir o projeto diretamente pelo arquivo `index.html`.

Outra opção é usar uma extensão como **Live Server** no VS Code:

1. Clone o repositório:

```bash
git clone https://github.com/MatheusNeumannSilva/Site-para-matriculas.git
```

2. Entre na pasta do projeto:

```bash
cd Site-para-matriculas
```

3. Abra o arquivo `index.html` no navegador ou execute com Live Server.

## Deploy

O projeto está publicado via **GitHub Pages**:

```text
https://matheusneumannsilva.github.io/Site-para-matriculas/
```

Como é um projeto estático, o deploy usa diretamente os arquivos da branch `main`.

## Aprendizados trabalhados

- Organização de CSS em arquivos menores.
- Uso de `fieldset`, `legend`, `label`, `input`, `select` e `textarea`.
- Criação de componentes visuais para inputs, radios e checkbox.
- Uso de `:hover`, `:focus-within`, `:has()` e estados de formulário.
- Correção de caminhos relativos para compatibilidade com GitHub Pages.
- Versionamento com commits semânticos.

## Próximos passos possíveis

- Adicionar responsividade mais refinada para telas pequenas.
- Implementar validações com JavaScript.
- Conectar o formulário a um backend ou serviço de envio.
- Melhorar acessibilidade com mensagens de erro mais completas.
- Adicionar máscara para telefone e CEP.

## Autor

Desenvolvido por **Matheus Neumann Silva**.

[GitHub](https://github.com/MatheusNeumannSilva)

## Licença

Este projeto ainda não possui uma licença definida.
