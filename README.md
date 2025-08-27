# 🍏 Nutri — Landing Page (Projeto Pessoal)

Landing page de demonstração para um serviço de nutrição/nutricionista. Projeto pensado como peça de **portfólio**, com foco em apresentar marca, planos e chamadas para ação (CTAs).

---

## 🔖 Demo

> Link do site (substitua por seu link quando publicar):
> `https://k4ioedu.github.io/Landingpage-Nutri/`


---

## 🧩 Descrição

Página estática responsiva que apresenta:

* Hero com proposta de valor;
* Sessão de planos com cards comparativos;
* Botões de CTA (agendar/assinar);
* Espaço para depoimentos/avaliações (opcional);
* Links para redes sociais (exibir como demo — sem contatos reais).

> Observação: este repositório contém conteúdo de demonstração. Por padrão **não** há contatos reais inseridos.

---

## 🛠 Tecnologias

* HTML5
* CSS3 (puro) — pode ser convertido para SCSS se preferir
* JavaScript (vanilla) — jQuery é opcional

---


## 📁 Estrutura sugerida do projeto

```
/
├── index.html
├── README.md
├── LICENSE
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── img/
│       ├── logo.png
│       ├── tela-inicial.png
│       └── planos.png
├── docs/                # (opcional) build estático para GitHub Pages
```

> Alternativa (se usar um bundler / framework):

```
/src
  /assets
  index.html
/dist   # build final
```

---

## ▶ Como rodar localmente

Método simples (abra `index.html` no navegador):

1. Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-PROJETO.git
cd NOME-DO-PROJETO
```

2. Abra `index.html` no navegador.

Usando servidor simples (recomendado para evitar problemas com rotas/assets):

```bash
# Python 3
python -m http.server 8000
# então abra http://localhost:8000
```

---



## 🧭 Ideias de melhorias futuras

* Formulário de contato funcional (integração via Netlify Forms / Formspree / backend).
* Área administrativa para gerenciar planos (backend).
* Animações sutis e versão mobile-first refinada.
* A/B testing de CTAs para portfólio profissional.

---

## 📜 Licença

Este projeto é fornecido com a licença abaixo. Arquivo `LICENSE` incluído neste repositório.

```
MIT License

Copyright (c) ANO Seu Nome

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👤 Autor

`Kaio Fontenele` — substitua quando quiser divulgar publicamente seu nome ou portfólio.

