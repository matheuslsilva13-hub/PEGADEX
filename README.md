# Pegadex — Landing Page

Visão geral do conteúdo e das seções estruturadas no código do projeto.

---

## 📄 Estrutura da Página (HTML)

O arquivo `index.html` está dividido nas seguintes seções:

* **Topo (`<header class="topo">`):**
  * Logo com imagem e texto.
  * Menu de navegação com links internos (`Início`, `O que fazemos`, `Quem somos`, `Contato`).
  * Botão de chamada rápida para o WhatsApp.

* **Destaque Principal (`<section class="bloco-principal">`):**
  * Etiqueta de aviso sobre o serviço.
  * Título principal e texto curto sobre a empresa.
  * Botões de ação (`Mandar mensagem` e `Ver o que fazemos`).
  * Imagem de destaque.

* **Serviços (`<section class="bloco-servicos">`):**
  * Título e explicação da seção.
  * 4 cartões com ícones em emoji: *Anúncios Pagos*, *Google e Busca*, *Redes Sociais* e *Criação de Sites*.

* **Quem Somos (`<section class="bloco-sobre">`):**
  * Imagem ilustrativa da equipe.
  * Texto sobre a proposta da empresa.
  * Lista de diferenciais (respostas rápidas, relatórios e preço).

* **Contato (`<section class="bloco-contato">`):**
  * Informações de endereço, e-mail e telefone.
  * Formulário de contato com campos para *Nome*, *E-mail*, *WhatsApp* e *Mensagem*.

* **Rodapé (`<footer class="rodape">`):**
  * Resumo da marca e slogan.
  * Lista de links de navegação.
  * Links para redes sociais.
  * Mensagem de direitos autorais.

---

## 🎨 Estilização (CSS)

O arquivo `style.css` contém a formatação visual dos elementos:

* **Alinhamento:** Uso de `display: flex` para organizar o topo, alinhar os botões em linha, colocar imagem ao lado de texto e estruturar a grade de serviços.
* **Componentes Visuais:** * Estilos para botões (com e sem fundo preenchido, incluindo efeito `:hover`).
  * Cartões de serviço com bordas simples e fundo leve.
  * Formulário com caixas de texto ajustadas e destaque na seleção (`:focus`).
* **Medidas:** Espaçamentos, fontes e tamanhos configurados em valores fixos (`px`).
