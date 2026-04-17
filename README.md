# Volta ao Mundo — Canadá

Site educacional e interativo sobre o Canadá, desenvolvido como projeto da disciplina de **Desenvolvimento Web III** do curso de **Desenvolvimento de Sistemas** (DSM). Apresenta informações sobre a geografia, natureza, cidades, gastronomia e cultura canadense em uma landing page responsiva e animada.

---

## Funcionalidades

| Seção | Descrição |
|---|---|
| **Hero Carousel** | Slideshow com 5 imagens icônicas do Canadá em tela cheia |
| **Vídeo** | Vídeo do YouTube integrado para imersão no destino |
| **Informações Gerais** | Estatísticas animadas (área, população, economia) com CountUp.js |
| **Natureza** | Galeria das principais paisagens: Banff, Lago Moraine, Cataratas do Niágara |
| **Cidades** | Cards descritivos de Vancouver, Toronto e Québec |
| **Gastronomia** | Cards sobre poutine, xarope de bordo e donair |
| **Cultura** | Povos indígenas, bilinguismo, hóquei no gelo e arte Inuit |

**Extras de UX:**
- Navbar inteligente (some ao rolar para baixo, reaparece ao rolar para cima)
- Animações de entrada ao scroll via AOS
- Botão "voltar ao topo" flutuante
- Layout totalmente responsivo (mobile, tablet e desktop)

---

## Tecnologias

- **HTML5 / CSS3** — estrutura e estilização customizada com variáveis CSS
- **Bootstrap 4** — grid responsivo e carousel
- **jQuery 3** — dependência do Bootstrap
- **AOS** — animações ao scroll
- **CountUp.js** — contadores animados nas estatísticas
- **Google Fonts** — Playfair Display e Inter
- Sem backend — projeto estático puro

---

## Estrutura do Projeto

```
volta_ao_mundo/
├── index.html        # Página principal
├── style.css         # Estilos customizados
├── images/           # Imagens do site (jpg, webp, avif)
└── README.md
```

---

## Como executar

1. Clone ou faça o download do repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-canadaDSM.git
   ```
2. Abra a pasta no VS Code.
3. Inicie com a extensão **Live Server** ou abra `index.html` diretamente no navegador.

> Não há dependências de npm nem etapa de build — funciona direto do navegador.

---

## Compatibilidade

Navegadores modernos com suporte a ES6+, CSS Grid, Flexbox e Intersection Observer API:

- Chrome 80+
- Firefox 75+
- Edge 80+
- Safari 13.1+

---

## Autor

Desenvolvido por **Lucas Simões** — 2025  
Projeto acadêmico — Curso de Desenvolvimento de Sistemas (DSM)
