# Internet Baby Club — E-commerce Fanmade

> Projeto desenvolvido para a disciplina de Criação de Sites — Design de Mídias Digitais · FATEC

---

## Ideia do Site

A Internet Baby Club é uma loja virtual fanmade voltada para fãs de música e cultura pop. A loja vende produtos exclusivos como posters, camisetas, canecas, fanzines, pulseiras, cadernos, chaveiros, bonés, ecobags, entre outros.

---

## Objetivo

Desenvolver um site de e-commerce voltado para fãs de música e cultura pop, oferecendo uma experiência de compra exclusiva, estética Y2K nostálgica e moderna e produtos fanmade autorais, conectando criadores e fãs em um único espaço digital.

---

## Qual o Problema a Ser Resolvido?

Fãs que buscam produtos únicos que representem seus artistas favoritos não encontram em um único lugar produtos com curadoria, identidade visual e designs exclusivos. A Internet Baby Club resolve isso oferecendo uma vitrine digital pensada especialmente para esse público.

---

## Project Model Canvas

| Seção | Conteúdo |
|---|---|
| **Objetivo** | Criar um site de e-commerce para vender produtos para fãs de artistas com designs originais inspirados em cultura pop. |
| **Justificativa** | Fãs buscam produtos únicos que representem seus artistas. |
| **Produtos** | Um site onde fãs encontram produtos (posters, fanzine, camisetas, posters, etc.) com designs exclusivos. |
| **Requisitos Principais** | Catálogo por categoria, carrinho de compras, pagamento, login e cadastro, formulário de contato, versão mobile |
| **Premissas** | Identidade visual definida, acesso ao GitHub/Vercel, banco de dados no Firebase, catálogo com designs autorais |
| **Riscos** | Integração de pagamento complexa, prazo curto para funcionalidades, dependência de ferramentas externas |
| **Linha do Tempo** | Mar–Abr = Pré-projeto · Abr–Mai = Design e prototipagem · Mai–Jun = Desenvolvimento técnico · Entrega = 09/06/2026 |
| **Grupo de Entregas** | Pré-projeto, design no Figma, desenvolvimento técnico, deploy e documentação README |

---

## Infraestrutura

```
internet-baby-club/
├── index.html              # Página inicial
├── style.css               # Estilos do site
├── contato.html            # Formulário de contato
├── api/
│   └── contact.js          # Função serverless (Node.js) — Vercel
├── fonts/
│   └── Matangi.ttf         # Tipografia da marca
├── assets/
│   ├── img/
│   │   └── logo.png
└── README.md
```

### Tecnologias utilizadas

| Camada | Tecnologia |
|---|---|
| Front-end | HTML5, CSS3, JavaScript |
| Back-end / Serverless | Node.js (`api/contact.js`) |
| Banco de dados | Firebase (Firestore) |
| Deploy | Vercel |
| Versionamento | GitHub |
| Prototipação | Figma |
| Gestão do projeto | Project Libre |

### Como funciona

1. O site é hospedado na **Vercel** via integração com o repositório GitHub
2. Ao enviar o formulário de contato, a requisição vai para a função serverless `api/contact.js`
3. A função usa variáveis de ambiente (configuradas na Vercel) para acessar o **Firebase**
4. Os dados do contato são gravados no **Firestore**
5. Atualizações no GitHub fazem deploy automático na Vercel

---

## Identidade Visual

| Elemento | Definição |
|---|---|
| **Cor principal** | `#70B8E0` — azul |
| **Cor secundária** | `#794199` — roxo |
| **Cor de destaque** | `#95CEA5` — verde |
| **Fundo** | `#FCFCED` — creme |
| **Tipografia** | Matangi |
| **Estética** | Y2K — nostálgica e moderna  |

---

## Cronograma (Project Libre)

> Arquivo `.pod` disponível no repositório. Abrir com o [Project Libre](https://www.projectlibre.com/).

| Fase | Início | Término | Entregáveis |
|---|---|---|---|
| **Pré-Projeto** | 31/03/2026 | 07/04/2026 | Project Libre, Canvas, Wireframes, README inicial |
| **Identidade Visual** | 07/04/2026 | 11/04/2026 | Paleta, tipografia, mascotes aplicados |
| **Design das Telas** | 14/04/2026 | 16/05/2026 | Menus, login, carrinho, pagamento, mobile |
| **Prototipagem no Figma** | 10/05/2026 | 16/05/2026 | Todas as telas prototipadas |
| **Desenvolvimento Técnico** | 17/05/2026 | 04/06/2026 | Programação, Firebase, testes, deploy |
| **Entrega** | 04/06/2026 | 09/06/2026 | README final, apresentação, link Vercel |

---

## O que foi feito até agora

- [x] Identidade visual definida (logo, paleta, tipografia, mascotes, elementos Y2K)
- [x] Project Model Canvas
- [x] Cronograma no Project Libre (Gráfico de Gantt)
- [x] Repositório GitHub criado e configurado
- [x] Firebase configurado
- [x] Função serverless `api/contact.js` criada
- [x] Formulário de contato em HTML
- [x] Página inicial (`index.html`) com design Y2K aplicado
- [x] CSS separado em arquivo próprio (`style.css`)
- [ ] Wireframe no Figma (em andamento)
- [ ] Deploy na Vercel
- [ ] Demais páginas do site

## Prompts utilizados (IA)

**Prompt — criação do design da homepage:**
```
cria algo criativo, baseado nos anos 2000 mas moderno e fofo ao mesmo tempo, a marca é praticamente toda arredondada, tem a logo tipografica, os grafismos de cada cor, os gatinhos de cada cor e formato, consegue criar algo a partir disso?
```

**Link do site e da apresentação canva com o cronograma do projeto e project model canvas:
apresentação: https://canva.link/4l0argni3aaxrvl 
site: https://internet-baby-club-homepage.vercel.app/ 

## Desenvolvedora

**Carolina Santos** — Design de Mídias Digitais · FATEC
Responsável pelo desenvolvimento completo do site (identidade visual, front-end, back-end serverless, infraestrutura e documentação).
