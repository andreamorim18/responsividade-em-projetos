# 🎯 Desafio Frontend - Projetos Responsivos

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Três projetos responsivos desenvolvidos com arquitetura CSS moderna, metodologia BEM e filosofia Mobile First.**

[Ver Demo](https://darkazerazs.github.io/desafio-frontend/) · [Reportar Bug](https://github.com/darkazerazs/desafio-frontend/issues)

</div>

---

## 📋 Sobre o Projeto

Este repositório contém três projetos práticos desenvolvidos como parte de um desafio de frontend, demonstrando habilidades em:

- Desenvolvimento de layouts responsivos
- Arquitetura CSS escalável e reutilizável
- Boas práticas de acessibilidade
- Código limpo e bem documentado

---

## 🚀 Projetos

### ✈️ Perfil de Viagens
Página de perfil pessoal para viajantes com:
- Hero section com estatísticas
- Cards de destinos visitados
- Mapa de progresso por continente
- Galeria de fotos em grid

### 📰 Portal de Notícias
Layout editorial completo com:
- Manchetes principais e secundárias
- Grid de notícias responsivo
- Sidebar com "Mais Lidas" e Newsletter
- Seção de colunistas/opinião

### 📝 Formulário de Matrícula
Formulário institucional multi-step com:
- Indicador de progresso
- Validação de campos
- Máscaras de input (CPF, CEP, telefone)
- Upload de documentos com feedback visual

---

## 🛠️ Tecnologias e Metodologias

| Tecnologia | Descrição |
|------------|-----------|
| **HTML5 Semântico** | Uso de tags como `<main>`, `<section>`, `<article>`, `<header>`, `<footer>` |
| **CSS Variables** | Design Tokens centralizados para cores, tipografia e espaçamentos |
| **CSS Grid & Flexbox** | Layouts modernos sem dependência de frameworks |
| **Metodologia BEM** | Nomenclatura de classes organizada (Block__Element--Modifier) |
| **Mobile First** | Desenvolvimento partindo do mobile para desktop |
| **clamp()** | Tipografia e espaçamentos fluidos sem media queries excessivas |

---

## 📐 Estratégia de Breakpoints

Utilizamos apenas **3 breakpoints** para simplicidade e manutenibilidade:

| Dispositivo | Media Query | Características |
|-------------|-------------|-----------------|
| 📱 Mobile | `< 48em` | Layout single column, touch-friendly |
| 📱 Tablet | `≥ 48em` (768px) | Layout 2 colunas |
| 🖥️ Desktop | `≥ 64em` (1024px) | Layout completo, multi-colunas |

A tipografia e espaçamentos usam `clamp()` para escalar suavemente entre os breakpoints.

---

## 📁 Estrutura de Pastas

```
desafio-frontend/
│
├── 📄 index.html                    # Hub de navegação principal
├── 📄 README.md                     # Documentação
│
├── 📂 css/
│   ├── 📂 global/                   # Estilos compartilhados (DRY)
│   │   ├── reset.css                # Normalização cross-browser
│   │   ├── tokens.css               # Design Tokens (variáveis)
│   │   ├── base.css                 # Tipografia + Utilities
│   │   └── global.css               # Importa todos os globais
│   │
│   └── 📂 projects/                 # Estilos específicos por projeto
│       ├── perfil-viagens.css
│       ├── portal-noticias.css
│       └── formulario-matricula.css
│
├── 📂 perfil-viagens/
│   └── index.html
│
├── 📂 portal-noticias/
│   └── index.html
│
└── 📂 formulario-matricula/
    └── index.html
```

---

## 🎨 Design Tokens

Os tokens estão centralizados em `css/global/tokens.css`:

```css
/* Cores */
--gray-50 até --gray-950
--blue-50 até --blue-900
--green-50 até --green-900
--red-50 até --red-900
--amber-50 até --amber-900

/* Tipografia Fluida */
--text-xs até --text-6xl  /* Usa clamp() */

/* Espaçamentos */
--space-1 até --space-64  /* Escala baseada em 4px */

/* Efeitos */
--shadow-xs até --shadow-2xl
--radius-sm até --radius-full
```

---

## 🏃‍♂️ Como Executar

### Localmente
1. Clone o repositório:
   ```bash
   git clone https://github.com/darkazerazs/desafio-frontend.git
   ```
2. Abra o `index.html` no navegador

### Via GitHub Pages
Acesse: `https://darkazerazs.github.io/desafio-frontend/`

---

## ✅ Checklist de Qualidade

- [x] HTML semântico e acessível
- [x] Classes CSS seguindo metodologia BEM
- [x] Sem "magic numbers" (valores fixos arbitrários)
- [x] Design Tokens para consistência visual
- [x] Responsivo Mobile First
- [x] Navegação por teclado funcional
- [x] Labels e ARIA labels para acessibilidade
- [x] Focus states visíveis
- [x] Código limpo e comentado

---

## 📸 Screenshots

<details>
<summary>🖼️ Ver Screenshots</summary>

### Hub Principal
![Hub](https://via.placeholder.com/800x400?text=Hub+de+Navegação)

### Perfil de Viagens
![Viagens](https://via.placeholder.com/800x400?text=Perfil+de+Viagens)

### Portal de Notícias
![Notícias](https://via.placeholder.com/800x400?text=Portal+de+Notícias)

### Formulário de Matrícula
![Matrícula](https://via.placeholder.com/800x400?text=Formulário+de+Matrícula)

</details>

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos de:

- **Arquitetura CSS DRY** - Estilos globais compartilhados entre projetos
- **CSS Custom Properties** - Variáveis CSS para Design Tokens
- **Funções CSS modernas** - `clamp()`, `min()`, `max()` para responsividade fluida
- **Grid Layout avançado** - `auto-fit`, `minmax()`, áreas nomeadas
- **Acessibilidade Web** - Semântica, ARIA, navegação por teclado

---

## 👨‍💻 Autor

**André**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Darkazerazs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrelfsantos)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Darkazerazs)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">

Feito com 💙 e muito CSS

⭐ Se este projeto te ajudou, deixe uma estrela!

</div>
