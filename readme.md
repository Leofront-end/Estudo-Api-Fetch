# 🔍 Rick and Morty Character Finder

Este projeto é uma aplicação web simples que permite ao usuário buscar informações sobre personagens da série **Rick and Morty** utilizando a [Rick and Morty API](https://rickandmortyapi.com/).

---

## 💡 Funcionalidades

- Busca de personagem pelo **ID**.
- Exibição de informações selecionadas como:
  - Nome
  - Status
  - Espécie
  - Gênero
  - Planeta de origem
  - Lista de episódios
- Exibição da **imagem do personagem**.
- Botão de **reset** para reiniciar a pesquisa.

---

## 🛠️ Tecnologias Utilizadas

- HTML  
- CSS  
- JavaScript Vanilla  
- Rick and Morty API

---

## 📦 Estrutura do Código

### Principais Elementos

- `fetchApi(value)`  
  Função responsável por buscar os dados do personagem com base no ID fornecido.

- `buildResult(result)`  
  Renderiza dinamicamente no HTML os dados selecionados com base nos checkboxes marcados pelo usuário.

### Eventos

- `btnGo` dispara a busca e exibe os dados.
- `btnReset` recarrega a página para limpar os dados anteriores.

### Organização de Chaves

As informações são organizadas em arrays de chaves (`keys`) e nomes mais legíveis (`newKeys`) para exibir ao usuário.

---

## 🧪 Como Usar

1. Digite um **ID válido** de personagem no campo de entrada.
2. Marque os **checkboxes** com as informações que deseja visualizar.
3. Clique no botão **Buscar**.
4. Os dados aparecerão abaixo com a **imagem do personagem**.
5. Clique em **Resetar** para realizar uma nova busca.

---

## 🖼️ Exemplo de Uso

Se você digitar o ID `1`, verá as informações do personagem **Rick Sanchez**, como nome, status, espécie etc.
