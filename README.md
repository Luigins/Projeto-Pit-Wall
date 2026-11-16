# 🏎️ PITWALL — GP de São Paulo

Página web temática de Fórmula 1 desenvolvida como projeto de estudo em **HTML5** e **CSS3**, simulando um portal oficial de informações, classificação e venda de ingressos para o **Grande Prêmio de São Paulo** no Autódromo de Interlagos.

---

## 📋 Sobre o Projeto

O **PitWall** apresenta uma interface moderna inspirada no universo do automobilismo, combinando paleta escura (*dark mode*), tipografia esportiva e elementos gráficos característicos das pistas de corrida, como zebras e recortes diagonais.

> **Nota:** Os pontos, posições e valores exibidos nas tabelas e formulários são meramente ilustrativos para fins de estudo.

---

## ✨ Seções e Funcionalidades

- **Cabeçalho Fixo / Navegação (`<header>`):** Logotipo estilizado (`PITWALL`), links de navegação interna (`Pilotos`, `Classificação`, `Ingressos`) e botão de chamada para ação (`Comprar Ingresso`).
- **Banner Principal (`.hero`):**
  - Destaque para o evento no Autódromo de Interlagos (Novembro de 2026).
  - Corte diagonal estilizado com faixa vermelha utilizando `clip-path: polygon()`.
  - Indicadores técnicos do circuito (`71 voltas`, `4.309 km por volta`, `15 curvas`).
  - Faixa inferior simulando a zebra da pista criada puramente com CSS (`repeating-linear-gradient`).
- **Grid de Pilotos (`#pilotos`):** Tabela apresentando pilotos do grid, números dos carros e suas respectivas equipes (Ferrari, McLaren, Mercedes e Audi).
- **Classificação (`#classificacao`):** Tabela de pontuação do campeonato com destaque para o líder, além de barra de filtros por nome/equipe.
- **Ingressos e Reserva (`#ingressos`):**
  - Layout dividido em duas colunas com CSS Grid.
  - Tabela de setores e valores (`Arquibancada A`, `Setor da Reta` e `Box VIP`) com alerta de disponibilidade.
  - Formulário completo para reserva de ingressos, seleção de data, quantidade, envio de foto da torcida para o telão e recado para o piloto.

---

## 🛠️ Tecnologias e Técnicas Utilizadas

- **HTML5 Semântico:** Uso de tags estruturais (`header`, `nav`, `section`, `table`, `form`, `footer`) e validações nativas de formulário.
- **CSS3 Moderno:**
  - **Variáveis CSS (`:root`):** Padronização das cores (`--black`, `--red`, `--white`, `--panel`) e esquema escuro nativo (`color-scheme: dark`).
  - **CSS Grid & Flexbox:** Alinhamento do cabeçalho, cartões de preços e colunas do formulário.
  - **Formas Geométricas e Gradientes:** `clip-path` para cortes diagonais responsivos e `repeating-linear-gradient` para a textura da zebra.
- **Google Fonts:** Tipografia **Titillium Web** (pesos de 300 a 900).

---

## 📁 Estrutura de Pastas

```text
Meu pit-wall/
├── index.html       # Estrutura principal da página
├── styles.css       # Estilização, layout responsivo e efeitos visuais
├── img/
│   └── foto2.png    # Imagem de destaque do carro na pista
└── README.md        # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

1. Faça o download ou clone este repositório.
2. Certifique-se de que os arquivos `index.html`, `styles.css` e a pasta `img/` estejam no mesmo diretório.
3. Abra o arquivo `index.html` diretamente em qualquer navegador web (Chrome, Edge, Firefox) ou utilize a extensão **Live Server** no VS Code.

---

## 👨‍💻 Autor

Desenvolvido por **Luigi Teixeira Marusso** como projeto prático de estudo em HTML e CSS.
