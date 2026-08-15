# FreshFold - Landing Page de Serviço de Lavanderia

Este projeto consiste em uma Landing Page responsiva e moderna desenvolvida para promover um serviço premium de lavanderia, passadoria e entrega ("FreshFold"). O foco do design é transmitir limpeza, confiança e conveniência através de um layout limpo, boa tipografia e imagens de alta qualidade.

## 🚀 Contexto do Projeto

O objetivo principal desta página é divulgar serviços de lavanderia para usuários que buscam praticidade. A página conta com as seguintes seções estruturais:
- **Hero Section**: Uma chamada principal impactante oferecendo serviços sem esforço, acompanhada de uma imagem de um ambiente de lavanderia moderna.
- **Serviços Oferecidos (Cards)**: Layout em formato de "grid" descrevendo os principais serviços prestados:
  - Lavagem Profunda
  - Passadoria e Dobra
  - Coleta e Entrega
- **Processo/Detalhes Adicionais**: Uma área explicando o cuidado detalhado com os tecidos.
- **Rodapé (Footer)**: Chamada final para ação (CTA) e informações de contato.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias fundamentais da web (sem o uso de frameworks pesados para garantir alta performance e leveza):

- **HTML5 (Semântico)**: Estruturação com tags claras (`<header>`, `<main>`, `<section>`, `<article>`) garantindo boa acessibilidade e SEO.
- **CSS3 (Vanilla)**:
  - **Variáveis CSS** (`:root`) para a paleta de cores e tipografia, permitindo um "Design System" consistente e fácil de atualizar.
  - **CSS Grid & Flexbox** para estruturação responsiva dos layouts (ex: posicionamento dos serviços e layout de seções divididas).
  - Animações e efeitos de *hover* suaves para melhorar a interatividade com o usuário.
- **Fontes**: *Inter* (via Google Fonts), garantindo leitura clara e design moderno.
- **Imagens Geradas por IA**: Fotografias com estética premium elaboradas para aumentar a percepção de valor do negócio (encontradas na pasta `/images`).

## 📁 Estrutura de Arquivos

```
/Landing Page
│
├── index.html     # Estrutura principal da página (conteúdo e marcação).
├── style.css      # Regras de estilo, design system (variáveis) e responsividade.
├── DESIGN.md      # Especificação completa de design (cores, tipografia, layout).
├── README.md      # Este arquivo, contendo o contexto e documentação do projeto.
└── images/        # Diretório com as imagens utilizadas:
    ├── laundry_hero.jpg
    ├── laundry_washing.jpg
    ├── laundry_folding.jpg
    └── laundry_delivery.jpg
```

## 💻 Como Rodar o Projeto

Como o projeto é estático e puramente front-end (HTML/CSS), não é necessário nenhum servidor complexo ou etapa de compilação.
Basta dar um duplo clique no arquivo `index.html` para abri-lo no seu navegador padrão (Google Chrome, Firefox, Edge, Safari, etc).
Se você estiver usando uma IDE como o VS Code, a extensão **Live Server** pode ser usada para testar alterações ao vivo.
