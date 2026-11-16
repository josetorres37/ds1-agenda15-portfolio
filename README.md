# Portfólio pessoal - Jose Flavio Torres

**Aluno:** Jose Flavio Torres  
**Curso:** Técnico em Desenvolvimento de Sistemas  
**Instituição:** Centro Paula Souza (CPS)

----

## Descrição do portfólio

Este é o meu portfólio pessoal acadêmico, desenvolvido como atividade da **Agenda 15 - Desenvolvimento de Sistemas I**. O site apresenta meu perfil profissional, habilidades técnicas, projetos realizados e formas de contato, com layout responsivo e design moderno.

O objetivo é mostrar minha evolução, com foco em desenvolvimento web (HTML, CSS, Bootstrap) e lógica de programação com Python.

---

## Tecnologias utilizadas

- **HTML5** – Estrutura semântica das páginas
- **CSS3** – Estilização personalizada e animações
- **Bootstrap 5** – Layout responsivo e componentes
- **Devicon** – Ícones das tecnologias
- **Bootstrap Icons** – Ícones gerais
- **JavaScript** (via Bootstrap Bundle) – Funcionamento do carousel e menu

----

## Link do site publicado

🔗 **GitHub pages:** [https://josetorres37.github.io/seu-repositorio/](https://josetorres37.github.io/seu-repositorio/)  

> Substitua `seu-repositorio` pelo nome real do repositório após publicar no GitHub Pages.

----

## Link do repositório

📂 **GitHub:** [https://github.com/josetorres37](https://github.com/josetorres37)

----

## Funcionamento do projeto

O site é uma página única (Single Page Application) com navegação suave entre as seções:

1. **Navbar** – Menu fixo no topo com links âncora para todas as seções.
2. **Carousel** – Banner rotativo com 3 slides apresentando o portfólio.
3. **Perfil** – Foto, descrição profissional, localização, formação e tecnologias.
4. **Habilidades** – Barras de progresso mostrando o nível de domínio em cada tecnologia.
5. **Projetos** – Cards com descrição e links para os repositórios no GitHub.
6. **Contato** – Botões com e-mail, GitHub e LinkedIn funcionais.
7. **Footer** – Rodapé com créditos.

----

## Recurso novo adicionado

Foram implementados **dois recursos novos** além do que foi feito em aula:

### 1. Animações de Hover nos Cards de Projetos
- Ao passar o mouse sobre os cards de projetos, eles sobem (`translateY`) e ganham sombra mais intensa.
- A imagem do projeto também aumenta levemente (`scale`).
- Implementado com CSS puro (`transition` + `:hover`).

### 2. Seção de habilidades com progress bars
- Nova seção dedicada às habilidades técnicas.
- Cada tecnologia possui uma barra de progresso animada mostrando o nível de domínio.
- Cards com efeito de elevação no hover.
- Cores personalizadas para cada tecnologia.

----

## Como o recurso foi implementado

### Animações de Hover
```css
.project-card {
  transition: transform 0.35s ease, box-shadow 0.35s ease;
}
.project-card:hover {
  transform: translateY(-12px);
  box-shadow: 0 1rem 2rem rgba(0, 0, 0, 0.18) !important;
}
.project-card:hover .card-img-top {
  transform: scale(1.05);
}
```

### Progress Bars (Habilidades)
Utilizei os componentes nativos do Bootstrap (`.progress` e `.progress-bar`) combinados com CSS personalizado para altura, bordas arredondadas e transição suave da largura.

---

## Contato

- **E-mail:** jose.torres5@aluno.cps.sp.gov.br
- **GitHub:** [josetorres37](https://github.com/josetorres37)
- **LinkedIn:** [Jose Flavio Torres](https://www.linkedin.com/in/jose-flavio-torres-784934430)
- **Localização:** São Paulo / SP

---
