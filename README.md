# DevOps Summit 2025

> Site oficial (simples) do **DevOps Summit 2025** — evento com palestras, painéis e workshops sobre práticas modernas de DevOps, Observability, CI/CD e automação.

---

## 🔎 Visão geral
Este repositório contém a versão estática do site do evento: `index.html`, `style.css` e a pasta `assets/` com imagens. O objetivo é ser um layout limpo e responsivo para divulgação do evento, com ênfase em um tema escuro moderno.

Principais características:
- Layout responsivo (grid para palestrantes).
- Cards com efeito hover.
- Menu com underline animado.
- Seções: Hero, Agenda, Palestrantes e Footer.
- Fácil de hospedar (GitHub Pages / static hosting).

---

## 🧭 Estrutura do repositório
devops-summit/
├─ index.html
├─ style.css
├─ assets/
│ ├─ matteo.jpg
│ ├─ adison.jpg
│ └─ matheus.jpg
├─ README.md
└─ LICENSE

yaml
Copiar código

---

## 🚀 Como rodar localmente
Você pode abrir `index.html` diretamente no navegador ou rodar um servidor local (recomendado).

### Opção 1 — Python (rápido)
No terminal, dentro da pasta do projeto:
```bash
# Python 3
python -m http.server 8000
Abra http://localhost:8000 no navegador.

Opção 2 — Live Server (VS Code)
Instale a extensão Live Server e clique em "Go Live" — o site será servido e recarregado automaticamente ao salvar mudanças.

📦 Stack e ferramentas
HTML5 + CSS3 (puro)

Layout responsivo com CSS Grid / Flexbox

Hospedagem sugerida: GitHub Pages, Netlify ou Vercel

✨ Como personalizar
Alterar cores/tema: abra style.css e edite as variáveis CSS em :root (--primary, --accent, --bg, etc.).

Mais palestrantes: duplique um <article class="profile-card"> em index.html e ajuste a imagem/texto.

Adicionar seção: crie uma nova <section class="section">...</section> no index.html e estilize se necessário.

🤝 Contribuindo
Contribuições são bem-vindas!

Fork deste repositório.

Crie uma branch com sua feature: git checkout -b feature/nome-da-feature.

Commit suas alterações: git commit -m "Minha feature".

Envie para seu fork: git push origin feature/nome-da-feature.

Abra um Pull Request aqui.

Por favor, descreva as mudanças e inclua screenshots quando aplicar alterações visuais.

📝 To-do (sugestões)
 Área para inscrição (formulário / Mailchimp).

 Página individual para cada palestra.

 Responsividade/UX para dispositivos muito pequenos.

 Otimização das imagens (WebP).

 Testes de acessibilidade (contraste, labels ARIA).

 ⚖️ Licença

Este projeto está sob a licença MIT — sinta-se livre para usar e adaptar. (Adicione um arquivo LICENSE com o texto MIT se desejar.)