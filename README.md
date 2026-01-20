# Currículo HTML com Exportação para PDF

Este é um projeto de currículo profissional em HTML que pode ser facilmente personalizado e exportado para PDF.

## 🎯 Características

- ✨ Design profissional e moderno
- 📱 Totalmente responsivo (adapta-se a diferentes tamanhos de tela)
- 🖨️ Otimizado para impressão e exportação em PDF
- ✏️ Fácil de editar e personalizar
- 🚀 Não requer instalação - funciona direto no navegador

## 📋 Como Usar

### Visualizar o Currículo

1. **Opção 1 - Abrir localmente:**
   - Faça o download ou clone este repositório
   - Abra o arquivo `index.html` em seu navegador preferido

2. **Opção 2 - GitHub Pages:**
   - Acesse: `https://seuusuario.github.io/curriculo/`
   - (Será necessário ativar GitHub Pages nas configurações do repositório)

### Exportar para PDF

Existem várias formas de exportar seu currículo para PDF:

#### Método 1: Botão de Exportação (Recomendado)
1. Abra o `index.html` no navegador
2. Clique no botão flutuante "📄 Exportar PDF" no canto inferior direito
3. Na janela de impressão, selecione "Salvar como PDF"
4. Escolha o local e salve o arquivo

#### Método 2: Atalho de Teclado
1. Abra o `index.html` no navegador
2. Pressione `Ctrl + P` (Windows/Linux) ou `Cmd + P` (Mac)
3. Selecione "Salvar como PDF"
4. Salve o arquivo

#### Método 3: Menu do Navegador
1. Abra o `index.html` no navegador
2. Vá em Arquivo → Imprimir
3. Selecione "Salvar como PDF" como destino
4. Salve o arquivo

## ✏️ Personalizando o Currículo

O arquivo `index.html` está estruturado de forma clara e fácil de editar. Você pode personalizar:

### Informações Pessoais
Edite as seguintes seções no HTML:
- **Nome:** Altere `<h1>Seu Nome Completo</h1>`
- **Título/Cargo:** Altere `<p class="subtitle">Desenvolvedor Full Stack</p>`
- **Contato:** Atualize os dados dentro de `.contact-info`

### Seções do Currículo

O currículo contém as seguintes seções que você pode modificar:

1. **Sobre Mim** - Apresentação pessoal
2. **Experiência Profissional** - Histórico de trabalho
3. **Formação Acadêmica** - Educação e cursos
4. **Habilidades Técnicas** - Tecnologias e ferramentas
5. **Projetos** - Projetos relevantes
6. **Idiomas** - Proficiência em línguas

### Dicas para Personalização

- **Adicionar nova experiência:** Copie um bloco `<div class="job">` existente e modifique
- **Adicionar habilidades:** Adicione mais `<span class="skill">Nova Skill</span>`
- **Alterar cores:** Modifique os códigos de cores no CSS (ex: `#3498db`)
- **Mudar fonte:** Altere `font-family` no CSS

## 🎨 Customização Avançada

### Cores
As principais cores usadas são:
- **Azul principal:** `#3498db`
- **Cinza escuro:** `#2c3e50`
- **Cinza médio:** `#7f8c8d`

Você pode alterar essas cores no CSS dentro da tag `<style>`.

### Layout
O layout é responsivo e se adapta automaticamente. Você pode ajustar:
- **Largura máxima:** Modifique `max-width: 900px` em `.container`
- **Espaçamentos:** Ajuste valores de `padding` e `margin`

## 📝 Adaptando para Vagas Específicas

Para adaptar seu currículo para cada vaga:

1. **Clone o repositório** ou faça um branch para cada vaga
2. **Edite o `index.html`** destacando experiências e habilidades relevantes
3. **Ajuste a seção "Sobre Mim"** para alinhar com a descrição da vaga
4. **Reordene as seções** colocando as mais relevantes primeiro
5. **Exporte para PDF** e envie para a empresa

## 🌐 Publicando Online com GitHub Pages

Para disponibilizar seu currículo online:

1. Vá nas configurações do repositório (Settings)
2. Na seção "Pages"
3. Em "Source", selecione a branch `main` ou `master`
4. Clique em "Save"
5. Seu currículo estará disponível em `https://seuusuario.github.io/curriculo/`

## 📱 Compatibilidade

O currículo foi testado e funciona perfeitamente em:
- ✅ Google Chrome
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera

## 🤝 Contribuindo

Sinta-se à vontade para fazer melhorias neste template! Pull requests são bem-vindos.

## 📄 Licença

Este projeto é livre para uso pessoal e profissional.

---

**Dica:** Mantenha diferentes versões do seu currículo em branches separados do Git para facilitar a adaptação para diferentes vagas!