# Docx to PDF Converter

Este é um projeto simples para converter arquivos `.docx` em `.pdf` diretamente no navegador, utilizando tecnologias modernas como **Mammoth.js** e **PDF-lib**.

## 🛠️ Funcionalidades

- Carregue um arquivo `.docx` e o converta para `.pdf` sem necessidade de back-end.
- Interface amigável e minimalista.
- Totalmente funcional no navegador, sem necessidade de instalação de software adicional.

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura da aplicação.
- **CSS3**: Estilização e design.
- **JavaScript**: Lógica de conversão e interação com o usuário.
- **[Mammoth.js](https://github.com/mwilliamson/mammoth.js)**: Para extrair texto de arquivos `.docx`.
- **[PDF-lib](https://pdf-lib.js.org/)**: Para criar e manipular arquivos `.pdf`.

## 📋 Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/docx-to-pdf-converter.git
    cd docx-to-pdf-converter
    ```
2. Certifique-se de que todos os arquivos estão na mesma pasta:
   - `index.html`
   - `style.css` (pasta `/static/`).
3. Abra o arquivo `index.html` em qualquer navegador moderno (Google Chrome, Firefox, etc.).
4. Carregue o arquivo `.docx` no input e clique em **"Converter para PDF"**.
5. O navegador fará o download do PDF gerado automaticamente.

## 🎨 Personalização

- O estilo pode ser ajustado no arquivo `style.css`. Ele está localizado na pasta `/static/` e segue um layout minimalista.
- Caso queira alterar o comportamento, edite o arquivo JavaScript embutido no `index.html`.

## 📂 Estrutura do Projeto
docx-to-pdf-converter/ │ ├── index.html # Estrutura principal do projeto ├── /static/ │ └── style.css # Estilo do site └── README.md # Documentação do projeto


## 🖥️ Pré-requisitos

- Navegador moderno com suporte para ES6+ (como Chrome ou Firefox).
- Conexão com a internet para carregar as bibliotecas externas (Mammoth.js e PDF-lib).

## 📄 Licença

Este projeto é licenciado sob a [MIT License](https://opensource.org/licenses/MIT).

---

### ✨ Demonstração

Caso tenha interesse em ver como o projeto funciona, basta seguir as etapas acima ou hospedar os arquivos em uma plataforma de sua escolha, como [GitHub Pages](https://pages.github.com/) ou [Netlify](https://www.netlify.com/).

💡 **Dica**: Adapte o design e funcionalidades para atender às suas necessidades específicas!


