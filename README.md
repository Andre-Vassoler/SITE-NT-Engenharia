<h1 align="center">NT Soluções em Engenharia · Redesenho UX do Site Institucional</h1>

<p align="center">
  Projeto de UX Research &amp; Design para uma empresa real de engenharia civil industrial,<br>
  da entrevista com o cliente ao site responsivo em HTML, CSS e JavaScript.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/UX-Design%20Thinking-006e7f?style=flat-square" alt="UX · Design Thinking">
  <img src="https://img.shields.io/badge/responsivo-desktop%20%2B%20mobile-00535f?style=flat-square" alt="Responsivo">
</p>

<p align="center">
  <img src="docs/preview.jpg" alt="Prévia do site da NT Soluções em Engenharia no desktop e no celular" width="880">
</p>

<p align="center">
  <a href="https://andre-vassoler.github.io/SITE-NT-Engenharia/site_empresa.html"><b>Ver o site no ar</b></a>
  &nbsp;·&nbsp;
  <a href="docs/Analise_UX_NT_Engenharia.pdf"><b>Relatório completo (PDF)</b></a>
  &nbsp;·&nbsp;
  <a href="site_empresa.html"><b>Código-fonte</b></a>
</p>

---

## Sobre o projeto

Projeto acadêmico da disciplina de **Interação Humano-Computador (UX)**, curso de Análise e Desenvolvimento de Sistemas, feito em grupo de 6 pessoas.

O cliente é a **NT Soluções em Engenharia** (Novo Tempo Soluções em Engenharia), um escritório com 14 anos de mercado que faz **projetos** de engenharia civil (não executa obras). Seus principais clientes são indústrias de grande porte, cervejarias e shoppings.

### O problema

O site da empresa **saiu do ar por questões técnicas** e ficou exibindo uma mensagem de manutenção, o que zerou a presença digital. Sem vitrine online, potenciais clientes não conseguiam descobrir, avaliar nem contatar a empresa.

### O que o cliente pediu

Uma página institucional interativa que levasse o usuário até cada nicho de serviço, com destaque para **pré-engenharia** (tudo o que uma empresa precisa para orçar uma obra). O cliente também queria:
- imagens de projetos e navegação intuitiva;
- identidade visual na cor da marca, o verde petróleo, com visual sóbrio;
- **desfoque de dados sensíveis** de clientes nas fotos de obra.

---

## Processo de UX

| Etapa | O que fizemos |
|---|---|
| **Empatia** | Entrevista com o cliente por videochamada e Mapa de Empatia do gestor industrial |
| **Definição** | Persona principal (*Ricardo Souza, Diretor Industrial*) e priorização da pré-engenharia como nicho estratégico |
| **Jornada do Usuário** | 5 etapas: Descoberta → Consideração → Avaliação → Contato → Conversão |
| **Mapa de Valor** | Value Proposition Canvas: trabalhos, dores e ganhos do cliente × aliviadores e criadores de ganho |
| **Ideação** | Seções e funcionalidades, referências visuais, paleta e tipografia da marca |
| **Prototipação** | Wireframes e protótipo funcional em HTML/CSS/JS |
| **Teste** | Validação interna de responsividade, navegação, contraste e clareza dos CTAs |
| **Usabilidade** | Avaliação com base nas Heurísticas de Nielsen |

> **Principal insight:** a etapa de **Consideração** é o ponto crítico da jornada. Um site fora do ar ou desatualizado faz o decisor técnico abandonar a empresa antes mesmo de avaliar o portfólio. Por isso a solução prioriza disponibilidade e um portfólio organizado por nicho.

---

## Funcionalidades

- **Navegação fixa** com scroll suave entre as seções (página única com âncoras)
- **Serviços por especialidade** em abas: Pré-Engenharia, Estrutural, Arquitetura, Consultoria e Verificação
- **Mercados de atuação** e **linha do tempo** do processo de trabalho (do briefing ao projeto executivo)
- **Portfólio** com filtros por categoria e lightbox com descrição de cada projeto
- **Proteção de dados:** imagens com informações de clientes recebem o selo *"Dados protegidos"*
- **Certificações** da empresa (Quality Prime, Quality Champion, Quality Brasil e ANCEC)
- **Vídeo institucional** incorporado
- **Formulário de contato** com campos objetivos e botão de **WhatsApp**
- **Layout responsivo**, do celular ao desktop

## Telas

| Serviços por especialidade | Portfólio de projetos |
|---|---|
| <img src="docs/servicos.jpg" alt="Seção de serviços"> | <img src="docs/portfolio.jpg" alt="Seção de portfólio"> |
| **Mercados de atuação** | **Como trabalhamos** |
| <img src="docs/mercados.jpg" alt="Seção de mercados de atuação"> | <img src="docs/processo.jpg" alt="Seção de processo"> |
| **Certificações** | **Contato** |
| <img src="docs/certificacoes.jpg" alt="Seção de certificações"> | <img src="docs/contato.jpg" alt="Seção de contato"> |

---

## Tecnologias

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica (`nav`, `section`, `footer`) |
| **CSS3** | Layout com Grid e Flexbox, animações, media queries e variáveis CSS como *design tokens* |
| **JavaScript (ES6)** | Abas de serviços, filtros do portfólio, lightbox, menu mobile e scroll suave |
| **Google Fonts** | Syne (títulos e rótulos) + DM Sans (textos) |

Tudo está em **um único arquivo**, sem frameworks nem dependências de build.

### Identidade visual

| Token | Cor | Uso |
|---|---|---|
| `--pet` | `#006e7f` | Verde petróleo da marca (cor primária) |
| `--pet-dark` | `#00535f` | Verde petróleo escuro |
| `--off` | `#f7f9f9` | Fundo off-white frio |
| `--text` | `#1a2a2d` | Texto quase preto esverdeado |

---

## Como executar

Não precisa instalar nada:

1. Baixe ou clone o repositório
   ```bash
   git clone https://github.com/Andre-Vassoler/SITE-NT-Engenharia.git
   ```
2. Abra o arquivo `site_empresa.html` no navegador.

## Estrutura do repositório

```
SITE-NT-Engenharia/
├── site_empresa.html                  # site completo (HTML + CSS + JS)
├── README.md
└── docs/
    ├── Analise_UX_NT_Engenharia.pdf   # relatório completo do projeto
    └── *.jpg                          # capturas de tela usadas neste README
```

## Próximos passos sugeridos

- Conectar o formulário de contato a um serviço de envio (no protótipo ele ainda não envia mensagens)
- CMS para a empresa atualizar o portfólio sozinha
- Área de login para clientes acompanharem projetos em andamento
- Google Analytics e SEO avançado (sitemap, dados estruturados, Search Console)
- Testes de usabilidade com usuários reais do setor industrial
- Versão em inglês para multinacionais instaladas no Brasil

---

## Equipe

André Fiordiluglio Vassoler · Antônio Carlos Florêncio · Gustavo Fidelis Bueno · Vitor Oliveira Neves · André Fernandes Sobreira C. Dourado · Nathan Almeida Santos

<sub>Projeto acadêmico. As marcas, imagens de projetos e certificações pertencem à NT Soluções em Engenharia.</sub>
