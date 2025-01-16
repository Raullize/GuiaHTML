# GuiaHTML 🚀

Bem-vindo ao **GuiaHTML**! Aqui você encontrará explicações, anotações e dicas sobre HTML, desde os conceitos básicos até tópicos mais avançados. Este guia foi criado para iniciantes e programadores intermediários que queiram relembrar ou consolidar conhecimentos sobre HTML. Vamos lá! 🖥️

## O que é HTML? 🤔
HTML (*HyperText Markup Language*) é a linguagem padrão para a criação de páginas web. Ela estrutura o conteúdo das páginas por meio de marcações (tags).

## Preparando o Ambiente 🛠️
1. **Editor de Código**: Recomenda-se o uso do [Visual Studio Code (VSCode)](https://code.visualstudio.com/).
   - Instale a extensão "Live Server" para visualizar mudanças no navegador em tempo real. 🌐
2. **Estrutura Básica de um Arquivo HTML**:
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página</title>
</head>
<body>
    <h1>Bem-vindo ao GuiaHTML!</h1>
</body>
</html>
```

## Principais Tags e Conceitos 📖

### **Tags de Texto** 📝
- `<h1> a <h6>`: Títulos de diferentes níveis.
- `<p>`: Parágrafo.
- `<strong>` e `<em>`: Texto em **negrito** e *itálico*, respectivamente.
- `<br>`: Quebra de linha.
- `<hr>`: Linha horizontal.

```html
<h1>Título Principal</h1>
<p>Este é um parágrafo com <strong>negrito</strong> e <em>itálico</em>.</p>
<br>
<hr>
```

### **Comentários** 💬
Use comentários para documentar o código:
```html
<!-- Este é um comentário e não será exibido no navegador -->
```

### **Imagens** 🖼️
- Exibindo imagens com a tag `<img>`:
```html
<img src="caminho-da-imagem.jpg" alt="Descrição da imagem" width="300">
```
  - Atributos importantes: `src`, `alt`, `width`, `height`.

### **Links** 🔗
- Criando links com `<a>`:
```html
<a href="https://www.google.com" target="_blank">Visite o Google</a>
```
  - Atributos importantes: `href`, `target`.

### **Listas** 📋
- Listas não ordenadas:
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```
- Listas ordenadas:
```html
<ol>
    <li>Primeiro</li>
    <li>Segundo</li>
</ol>
```

### **Formulários** 📑
- Elementos principais:
```html
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">
    <button type="submit">Enviar</button>
</form>
```

### **Tabelas** 📊
- Criando tabelas simples:
```html
<table border="1">
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Maria</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

### **Div e Span** 🧩
- `<div>`: Divisão genérica para agrupar elementos.
- `<span>`: Elemento genérico para estilização inline.

### **Semântica e Acessibilidade** ♿

#### Semântica
As tags semânticas ajudam a dar significado ao conteúdo da página, facilitando a leitura tanto para desenvolvedores quanto para motores de busca (SEO). Exemplos de tags semânticas:
- `<header>`: Cabeçalho de uma página ou seção.
- `<footer>`: Rodapé de uma página ou seção.
- `<article>`: Conteúdo independente, como artigos de blog.
- `<section>`: Agrupa conteúdos relacionados dentro de uma página.
- `<nav>`: Navegação, usada para links de menu.
- `<main>`: Conteúdo principal da página.

Exemplo:
```html
<header>
    <h1>Bem-vindo ao meu site</h1>
</header>
<main>
    <article>
        <h2>Meu Primeiro Artigo</h2>
        <p>Este é um exemplo de artigo usando HTML semântico.</p>
    </article>
    <section>
        <h2>Seção Importante</h2>
        <p>Informações relevantes sobre o tema.</p>
    </section>
</main>
<footer>
    <p>&copy; 2025 - Todos os direitos reservados.</p>
</footer>
```

#### Acessibilidade
Acessibilidade em HTML é crucial para garantir que todos possam navegar e interagir com o conteúdo, incluindo pessoas com deficiências. Aqui estão algumas práticas:

1. **Imagens**:
   - Sempre adicione o atributo `alt` nas imagens para descrever seu conteúdo.
   ```html
   <img src="imagem.jpg" alt="Foto de uma paisagem ao pôr do sol">
   ```

2. **Elementos interativos**:
   - Use atributos `aria-*` (Accessible Rich Internet Applications) para fornecer informações adicionais a leitores de tela.
   ```html
   <button aria-label="Fechar menu">&times;</button>
   ```

3. **Formulários**:
   - Relacione `<label>` com os campos usando o atributo `for` e o `id` correspondente.
   ```html
   <label for="email">E-mail:</label>
   <input type="email" id="email" name="email">
   ```

4. **Teclas de acesso**:
   - Utilize o atributo `accesskey` para criar atalhos de teclado.
   ```html
   <a href="#conteudo" accesskey="1">Pular para o conteúdo</a>
   ```

5. **Contraste**:
   - Certifique-se de que o contraste de cores entre texto e fundo seja suficiente para facilitar a leitura.

6. **Estrutura e Navegação**:
   - Use tags semânticas para estruturar o conteúdo de forma lógica e intuitiva.

## 🌐 Recursos Adicionais
- [MDN Web Docs: HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3Schools: HTML](https://www.w3schools.com/html/)
- [HTML5 Cheat Sheet](https://htmlcheatsheet.com/)

---

Esperamos que este guia tenha sido útil para você! 😄 Continuaremos expandindo com mais dicas e exemplos.

🎯 **Contribuições são bem-vindas!** Caso queira adicionar algo, faça um pull request no repositório.
