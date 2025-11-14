# LearnPlus - Plataforma de Cursos Online

## 🖥️ Preview do Sistema

<div align="center">
  <img src="imagens/plataforma de cursos.png" alt="Tela Principal - LearnPlus" width="800">
  <br>
  <sup>Interface principal da plataforma LearnPlus</sup>
  <br>
  https://carloseduardogit.github.io/plataforma-de-cursos/
</div>

## 📋 Sobre o Projeto

A **LearnPlus** é uma plataforma de cursos online moderna e responsiva desenvolvida em HTML, CSS e JavaScript. A plataforma oferece uma interface intuitiva para usuários explorarem e se inscreverem em diversos cursos de programação e outras áreas do conhecimento.

## 🎯 Objetivo

O principal objetivo da LearnPlus é conectar alunos aos melhores instrutores em todo o mundo, proporcionando uma experiência de aprendizado online acessível, organizada e visualmente atrativa.

## ✨ Funcionalidades Principais

### 1. **Navegação Intuitiva**
- Header fixo com menu de navegação
- Barra de pesquisa integrada
- Perfil do usuário
- Navegação responsiva para dispositivos móveis

### 2. **Sistema de Filtros e Ordenação**
- **Filtros por Categoria**: Programação, Design, Marketing, Negócios, Fotografia, Idiomas, Música, Saúde
- **Ordenação**: Recomendados, Mais Recentes, Melhor Avaliados, Preço
- **Filtro por Nível**: Iniciantes, Intermediários, Avançados

### 3. **Catálogo de Cursos**
- Grid responsivo de cursos
- Cards informativos com:
  - Imagem representativa do curso
  - Título e descrição
  - Informações do instrutor
  - Duração do curso
  - Número de alunos
  - Avaliação e reviews
  - Preço e promoções
  - Badges destacadas (Mais Vendido, Popular, Novo, Promoção)

### 4. **Cursos Disponíveis**
- HTML5 CSS3 e JavaScript ES6 do Absoluto Zero ao Avançado
- JavaScript ES6 do Absoluto Zero ao Avançado
- TypeScript do Absoluto Zero ao Avançado
- React do Absoluto Zero ao Avançado
- React Native do Absoluto Zero ao Avançado
- Angular do Absoluto Zero ao Avançado

### 5. **Design Responsivo**
- Layout adaptável para desktop, tablet e mobile
- Grid que se ajusta automaticamente
- Menu responsivo que se transforma em hamburger menu em telas menores

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- **HTML5**: Estrutura semântica da página
- **CSS3**: 
  - Variáveis CSS para consistência de cores
  - Grid e Flexbox para layout
  - Media Queries para responsividade
  - Animações e transições
  - Design System com paleta de cores definida
- **JavaScript**: Interatividade básica
- **Font Awesome**: Ícones

### **Recursos Externos**
- CDN do Font Awesome para ícones
- Imagens de cursos via URLs externas

## 🎨 Design System

### **Paleta de Cores**
```css
:root {
    --primary: #3498db;      /* Azul principal */
    --secondary: #2ecc71;    /* Verde para badges */
    --accent: #e74c3c;       /* Vermelho para destaque */
    --dark: #2c3e50;         /* Azul escuro para textos */
    --light: #ecf0f1;        /* Cinza claro */
    --gray: #95a5a6;         /* Cinza para textos secundários */
    --light-gray: #f5f7fa;   /* Fundo da página */
}
```

### **Componentes Principais**

1. **Header/Navbar**
   - Logo com ícone de formatura
   - Menu de navegação com indicador de página ativa
   - Barra de pesquisa com ícone
   - Avatar do usuário

2. **Course Card**
   - Imagem do curso com badge
   - Informações do instrutor com avatar
   - Metadados (duração, alunos)
   - Sistema de avaliação por estrelas
   - Preço e ação "Ver Curso"

3. **Filtros e Categorias**
   - Select boxes para ordenação e filtros
   - Scroll horizontal de categorias
   - Estados ativo/hover com transições

## 📱 Responsividade

### **Breakpoints**
- **Desktop**: Acima de 992px
- **Tablet**: 768px - 992px
- **Mobile**: Abaixo de 768px

### **Adaptações Mobile**
- Menu vira coluna
- Barra de pesquisa ocupa largura total
- Grid de cursos vira coluna única
- Filtros ficam com scroll horizontal

## 🔧 Funcionalidades JavaScript

### **Interatividade Implementada**
1. **Filtros de Categoria**
   - Alternância de estado ativo
   - Feedback visual imediato

2. **Busca**
   - Captura do evento Enter
   - Simulação de busca com alerta

3. **Hover Effects**
   - Elevação dos cards ao passar o mouse
   - Transições suaves em botões e links

## 🚀 Como Usar

### **Para Estudantes**
1. Navegue pelas categorias ou use a barra de pesquisa
2. Filtre cursos por nível de dificuldade
3. Ordene por relevância, preço ou avaliação
4. Clique em "Ver Curso" para acessar detalhes

### **Para Desenvolvedores**
```html
<!-- Estrutura básica de um card de curso -->
<div class="course-card">
    <div class="course-image" style="background-image: url('...')">
        <div class="course-badge">Popular</div>
    </div>
    <div class="course-content">
        <h3 class="course-title">Título do Curso</h3>
        <!-- ... resto do conteúdo -->
    </div>
</div>
```

## 📈 Próximas Melhorias Potenciais

1. **Backend Integration**
   - Sistema de usuários real
   - Carrinho de compras
   - Processamento de pagamentos

2. **Funcionalidades Avançadas**
   - Busca em tempo real
   - Favoritos
   - Progresso do curso
   - Certificados

3. **UX/UI**
   - Modo escuro
   - Mais animações
   - Loading states

## 🌐 Estrutura do Site

```
LearnPlus/
├── Header (Navegação)
├── Main Content
│   ├── Filtros e Ordenação
│   ├── Categorias
│   └── Grid de Cursos (6 cursos)
└── Footer (Informações e Links)
```

## 📞 Contato e Suporte

- **Endereço**: Av. Paulista, 1000, São Paulo
- **Telefone**: (11) 9999-9999
- **Email**: contato@learnplus.com
- **Redes Sociais**: Facebook, Twitter, Instagram, LinkedIn

---

**© 2023 LearnPlus. Todos os direitos reservados.**

*Uma plataforma dedicada ao aprendizado contínuo e desenvolvimento profissional.*
