# 📅 Calendário de Férias e Feriados

![Licença MIT](https://img.shields.io/badge/License-MIT-blue.svg)

Um planejador de calendário interativo para marcar e gerenciar seus feriados, férias e datas importantes. Tudo salvo diretamente no seu navegador!

[Imagem do calendário em ação]
*(Recomendação: Tire um print da aplicação funcionando e insira aqui)*

## 📝 Sobre o Projeto

Este projeto é uma ferramenta web simples, mas poderosa, para visualizar um calendário anual e adicionar feriados e eventos personalizados. A ideia original era "usar um calendário para marcar as férias de acordo com as melhores datas", e esta ferramenta facilita exatamente isso.

Ele permite identificar facilmente os melhores períodos para férias, visualizando fins de semana e feriados personalizados em uma única tela. O melhor de tudo: **não requer banco de dados ou backend!** Todos os seus dados são salvos com segurança no `localStorage` do seu navegador.

## ✨ Funcionalidades Principais

* **Visualização Anual:** Veja todos os 12 meses de um ano selecionado de uma só vez.
* **Marcação de Feriados:** Adicione feriados personalizados com nome e data através de um formulário simples.
* **Fins de Semana Automáticos:** Sábados e domingos são automaticamente destacados.
* **Edição Rápida (Clique):** Clique em qualquer dia do calendário para adicionar ou editar um feriado rapidamente.
* **Remoção Rápida (Clique Direito):** Clique com o botão direito em um dia para remover um feriado personalizado.
* **Persistência Local:** Seus feriados são salvos no `localStorage` do navegador. Você pode fechar a aba e seus dados continuarão lá.
* **Listagem de Feriados:** Um painel "acordeão" lista todos os feriados salvos para o ano, permitindo a remoção individual.
* **Exportar Dados:** Exporte todos os seus dados (de todos os anos) para um arquivo `feriados.json` como backup.
* **Importar Dados:** Importe um arquivo `feriados.json` para mesclar dados em um novo navegador ou dispositivo.
* **Impressão:** Um botão dedicado para imprimir a visualização do calendário (via `window.print()`).

## 🚀 Como Usar

Como este é um projeto puramente front-end (HTML, CSS e JS), não há necessidade de instalação complexa.

1.  **Clone o repositório:**
    ```sh
    git clone [https://github.com/SEU-USUARIO/calendario_ferias.git](https://github.com/SEU-USUARIO/calendario_ferias.git)
    ```
2.  **Abra o arquivo:**
    Navegue até a pasta do projeto e abra o arquivo `index.html` (ou o nome principal do seu arquivo HTML) diretamente no seu navegador.

É isso! Você pode começar a adicionar seus feriados imediatamente.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído do zero, sem frameworks JavaScript, focando em funcionalidades puras de navegador:

* **HTML5:** Estrutura semântica.
* **CSS3:** Estilização moderna, incluindo Variáveis CSS, Grid e Flexbox.
* **JavaScript (ES6+):** Toda a lógica interativa, manipulação do DOM e gerenciamento do `localStorage`.
* **Bootstrap 5:** Utilizado para componentes de UI (como formulários, botões, navbar e acordeão) e layout responsivo.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.