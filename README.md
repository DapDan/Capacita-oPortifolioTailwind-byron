# Capacitação: Portfólio Tailwind - byron.solutions

Este é um projeto de portfólio pessoal moderno e responsivo desenvolvido por **Danilo Alexandre** durante o processo de capacitação na [byron.solutions](https://byron.solutions/). O projeto foi desenvolvido com foco em praticar a estilização rápida, componentização e design fluido utilizando **Tailwind CSS v4**.

---

## Tecnologias Utilizadas

O projeto utiliza as seguintes tecnologias e ferramentas:

- **HTML5** - Estruturação semântica da página.
- **Tailwind CSS v4.0** - Framework utilitário para estilização rápida, moderna e responsiva.
- **Google Fonts** - Integração da fonte *Inter* para uma tipografia limpa.
- **Fontes de Ícones/Imagens** - Imagens integradas da mascote Sally, além de links de redes sociais.

---

## Estrutura do Projeto

A estrutura de arquivos do projeto está organizada da seguinte forma:

```text
tailwind-byron/
├── img/                # Assets e imagens do projeto (logos, mascote)
├── src/
│   ├── index.html      # Página principal (estrutura HTML)
│   ├── input.css       # Estilos customizados e diretivas do Tailwind CSS (@theme)
│   └── output.css      # CSS compilado gerado pelo CLI do Tailwind
├── package.json        # Dependências do projeto (Tailwind CSS v4)
└── README.md           # Documentação do projeto
```

---

## Como Executar o Projeto Localmente

### 1. Pré-requisitos
Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### 2. Instalar Dependências
No diretório raiz do projeto, instale as dependências necessárias (Tailwind CSS e seu CLI):
```bash
npm install
```

### 3. Compilar o Tailwind CSS (Modo de Desenvolvimento)
Para rodar o compilador do Tailwind CSS em tempo real (atualizando o `output.css` sempre que houver alterações no `index.html` ou `input.css`):
```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

### 4. Abrir no Navegador
Após a compilação do CSS, basta abrir o arquivo `src/index.html` no seu navegador de preferência ou usar uma extensão como o *Live Server* no VS Code.

---

## Personalização do Tema (Tailwind v4)
No arquivo [input.css](file:///c:/Users/Danilo/Desktop/tailwind%20byron/src/input.css), utilizamos a nova sintaxe `@theme` do Tailwind CSS v4 para definir as cores e tipografia da identidade visual:

- **Cor Principal (main)**: `#8B5CF6` (Roxo)
- **Cor Secundária (secondary)**: `#F97316` (Laranja)
- **Fonte Principal (main)**: `"Inter", sans-serif`

---

## Projetos em Destaque no Portfólio
O portfólio exibe alguns dos meus principais projetos acadêmicos e pessoais:
1. **Nasa Space Apps - Meteor Hunters** (TypeScript)
2. **Snake Game** (C++ com Arduino Uno & display OLED)
3. **Compilador & Interpretador** (Desenvolvido em C para uma Mini-Linguagem)
4. **TCC MyPetRoutine** (Website de gestão pet utilizando CSS e tecnologias Web)
5. **Sistema Acadêmico** (Plataforma para gestão de notas construída em TypeScript)
6. **Capacitação Portfólio** (HTML básico)

---

## Autor

Desenvolvido por **Danilo Alexandre**.
- **LinkedIn**: [Danilo Alexandre](https://www.linkedin.com/in/danilo-alexandre-8149b2211/)
- **Instagram**: [@danilo_alexandre_pereira](https://www.instagram.com/danilo_alexandre_pereira)
- **GitHub**: [DapDan](https://github.com/DapDan)

Design criado sob as diretrizes da **byron.solutions**.
