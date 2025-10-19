# 🌎 Turismo Rota Certa

<div align="center">
  <img src="imagens/logoarrumada.png" alt="Logo Turismo Rota Certa" width="150">
  
  **Agência de Viagens - Pacotes Nacionais e Atendimento Personalizado**
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
  [![Responsive](https://img.shields.io/badge/Design-Responsive-brightgreen?style=for-the-badge)](https://web.dev/responsive-web-design-basics/)
  [![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)](https://github.com/seu-usuario/turismo-rota-certa)
</div>

---

## 📖 Sobre o Projeto

O **Turismo Rota Certa** é uma plataforma web moderna e responsiva desenvolvida para uma agência de viagens especializada em destinos turísticos nacionais brasileiros. O projeto apresenta uma interface elegante e intuitiva, oferecendo informações detalhadas sobre pacotes de viagem e experiências únicas pelo Brasil.

### 🎯 Características Principais

- 🏖️ **Showcase de Destinos**: Apresentação visual atrativa dos principais destinos brasileiros
- 📋 **Informações Completas**: Dados detalhados sobre cada pacote de viagem
- 📞 **Múltiplos Contatos**: Facilita comunicação direta com a agência
- 📱 **Design Responsivo**: Experiência otimizada para todos os dispositivos
- ⚡ **Performance**: Carregamento rápido e navegação fluida

---

## ✨ Funcionalidades

### 🏠 Página Inicial
- Hero section com apresentação da marca
- Grid responsivo com cards dos destinos
- Menu de navegação intuitivo
- Footer informativo com dados de contato

### 📄 Páginas de Destinos
- Galeria de imagens em alta qualidade  
- Descrições detalhadas de cada localização
- Depoimentos autênticos de clientes
- Informações sobre preços e duração dos pacotes

### 🔧 Recursos Técnicos
- Design Mobile First
- Compatibilidade cross-browser
- Otimização SEO
- Estrutura HTML semântica
- CSS moderno com Flexbox/Grid

---

## ✈️ Destinos Disponíveis

| 🏖️ Destino | 📍 Estado | 🌟 Principais Atrativos | ⏰ Duração |
|:----------:|:---------:|:----------------------:|:----------:|
| **Guarujá** | São Paulo | Praias urbanas, vida noturna | 5-7 dias |
| **Búzios** | Rio de Janeiro | Charme rústico, gastronomia | 4-6 dias |
| **Porto de Galinhas** | Pernambuco | Piscinas naturais, mergulho | 6-8 dias |
| **Manaus** | Amazonas | Floresta amazônica, ecoturismo | 7-10 dias |
| **Gramado** | Rio Grande do Sul | Arquitetura européia, festivais | 4-5 dias |

---

## 🛠️ Tecnologias

### Frontend
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna e responsiva
- **Flexbox & CSS Grid** - Layout flexível e avançado
- **Media Queries** - Design responsivo multi-dispositivo
- **Google Fonts** - Tipografia Golos Text

### Metodologias
- **Mobile First** - Desenvolvimento priorizando dispositivos móveis
- **BEM CSS** - Organização escalável de estilos
- **Progressive Enhancement** - Melhoria progressiva da experiência
- **Web Standards** - Conformidade com padrões web

---

## 📂 Estrutura do Projeto

```
desenvolvimento-site/
│
├── 📄 index.html              # Página inicial
├── 📄 guaruja.html           # Pacote Guarujá
├── 📄 buzios.html            # Pacote Búzios  
├── 📄 porto.html             # Pacote Porto de Galinhas
├── 📄 manaus.html            # Pacote Manaus
├── 📄 gramado.html           # Pacote Gramado
├── 🎨 style.css              # Estilos principais
├── 📁 imagens/               # Assets visuais
│   ├── destinos/             # Imagens dos destinos
│   ├── depoimentos/          # Fotos de clientes
│   └── logoarrumada.png      # Logo da empresa
└── 📋 README.md              # Este arquivo
```

---

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno
- Servidor local (opcional)

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/turismo-rota-certa.git
cd turismo-rota-certa/desenvolvimento-site
```

2. **Execução direta**
```bash
# Abra index.html no navegador
open index.html
```

3. **Com servidor local (recomendado)**
```bash
# Python
python -m http.server 5500

# Node.js
npx live-server --port=5500

# PHP  
php -S localhost:5500
```

4. **Acesse no navegador**
```
http://localhost:5500
```

---

## 📱 Responsividade

Desenvolvido com abordagem **Mobile First**:

| 📱 Dispositivo | 📐 Resolução | 🎨 Layout |
|:-------------:|:------------:|:---------:|
| Mobile | < 600px | Menu vertical, cards empilhados |
| Mobile Large | 600-768px | Layout adaptativo |
| Tablet | 768-900px | Grid 2 colunas |
| Desktop | > 900px | Layout completo |

### Breakpoints
```css
/* Mobile (base) */
@media (max-width: 600px) { /* Mobile específico */ }

/* Mobile Large */  
@media (max-width: 700px) { /* Footer ajustado */ }

/* Tablet */
@media (max-width: 900px) and (min-width: 601px) { /* Tablet */ }
```

---

## 🎨 Design System

### Cores
```css
#ffffff  /* Branco - Backgrounds */
#222222  /* Cinza Escuro - Textos principais */  
#444040  /* Cinza Médio - Textos secundários */
#f7f7f7  /* Cinza Claro - Backgrounds sutis */
#1572B6  /* Azul - Links e destaques */
```

### Tipografia
```css
Font Family: 'Golos Text', Arial, sans-serif
H1: 2.5rem | H2: 2rem | H3: 1.5rem | P: 1rem
```

---

## 📊 Performance

### Otimizações
- ✅ Imagens otimizadas
- ✅ CSS organizado e limpo
- ✅ HTML semântico
- ✅ Carregamento eficiente

### SEO
- ✅ Meta tags otimizadas
- ✅ Alt text em imagens
- ✅ Estrutura semântica
- ✅ Performance rápida

### Acessibilidade
- ✅ Contraste adequado
- ✅ Navegação por teclado
- ✅ Textos alternativos
- ✅ Estrutura lógica

---

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/nova-feature`)
3. Commit as mudanças (`git commit -m 'Add: Nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Chris**  
*Web Developer*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/seu-perfil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contato@rotacerta.com.br)

---

## 🙏 Agradecimentos

- 🎓 Faculdade pelo projeto AC2 - Web Design
- 🎨 Google Fonts pela tipografia
- 📷 Bancos de imagem pelos assets visuais
- 🌟 Comunidade dev pela inspiração

---

<div align="center">
  
**🚀 Desenvolvido com ❤️ para AC2 - Web Design**

**✈️ Explore o Brasil com a Rota Certa!**

[![AC2](https://img.shields.io/badge/Projeto-AC2-blue)](https://github.com/seu-usuario/turismo-rota-certa)
[![Web Design](https://img.shields.io/badge/Curso-Web%20Design-green)](https://github.com/seu-usuario/turismo-rota-certa)

**© 2025 Turismo Rota Certa - Todos os direitos reservados**

</div>

