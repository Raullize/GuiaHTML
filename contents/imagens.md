<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 🖼️ **Imagens**

As imagens são elementos fundamentais para tornar as páginas web mais atraentes e informativas. O HTML permite inserir e manipular imagens de diversas maneiras através da tag `<img>`.

## 🔍 **Sintaxe Básica**

```html
<img src="caminho-da-imagem.jpg" alt="Descrição da imagem">
```

## 📝 **Atributos Essenciais**

| Atributo | Descrição |
|----------|-----------|
| `src` | **Obrigatório**. Define o caminho (URL) da imagem |
| `alt` | **Obrigatório**. Texto alternativo para acessibilidade e SEO |
| `width` | Define a largura da imagem em pixels ou porcentagem |
| `height` | Define a altura da imagem em pixels ou porcentagem |
| `title` | Texto que aparece ao passar o mouse sobre a imagem |
| `loading` | Controla como a imagem é carregada (ex: `lazy` para carregamento preguiçoso) |

## 🛤️ **Tipos de Caminhos**

### Caminho Absoluto
```html
<img src="https://www.exemplo.com/imagens/foto.jpg" alt="Foto de exemplo">
```

### Caminho Relativo
```html
<!-- Imagem na mesma pasta do arquivo HTML -->
<img src="foto.jpg" alt="Foto de exemplo">

<!-- Imagem em uma subpasta -->
<img src="imagens/foto.jpg" alt="Foto de exemplo">

<!-- Imagem em uma pasta acima -->
<img src="../foto.jpg" alt="Foto de exemplo">
```

## 📊 **Dimensionamento de Imagens**

### Definindo Tamanho Fixo
```html
<img src="foto.jpg" alt="Foto" width="300" height="200">
```

### Definindo Apenas a Largura (mantém proporção)
```html
<img src="foto.jpg" alt="Foto" width="300">
```

### Usando Porcentagem (responsivo)
```html
<img src="foto.jpg" alt="Foto" width="100%">
```

## 🔄 **Formatos de Imagem Comuns**

| Formato | Uso Recomendado |
|---------|-----------------|
| **JPG/JPEG** | Fotografias e imagens com muitas cores e detalhes |
| **PNG** | Imagens que precisam de transparência ou qualidade nítida |
| **GIF** | Animações simples ou imagens com poucas cores |
| **SVG** | Gráficos, ícones e ilustrações que precisam ser escaláveis |
| **WebP** | Formato moderno com melhor compressão, suporte crescente |

## 🖌️ **Imagens Responsivas**

### Usando o atributo `srcset`
```html
<img 
  src="imagem-pequena.jpg" 
  srcset="imagem-pequena.jpg 300w,
          imagem-media.jpg 600w,
          imagem-grande.jpg 1200w"
  sizes="(max-width: 600px) 300px,
         (max-width: 1200px) 600px,
         1200px"
  alt="Imagem responsiva">
```

### Usando a tag `<picture>`
```html
<picture>
  <source media="(max-width: 600px)" srcset="imagem-mobile.jpg">
  <source media="(max-width: 1200px)" srcset="imagem-tablet.jpg">
  <img src="imagem-desktop.jpg" alt="Imagem adaptativa">
</picture>
```

## 🔗 **Imagens como Links**

```html
<a href="pagina.html">
  <img src="botao.jpg" alt="Clique aqui">
</a>
```

## 🎭 **Figuras com Legendas**

```html
<figure>
  <img src="grafico.jpg" alt="Gráfico de vendas">
  <figcaption>Figura 1: Vendas do primeiro trimestre de 2023</figcaption>
</figure>
```

### 📌 **Boas Práticas**

✅ Sempre use o atributo `alt` com descrições significativas.  
✅ Otimize as imagens para web (tamanho e compressão).  
✅ Use formatos apropriados para cada tipo de imagem.  
✅ Implemente imagens responsivas para diferentes dispositivos.  
✅ Defina dimensões para evitar saltos de layout durante o carregamento.  
✅ Considere o uso de `loading="lazy"` para melhorar o desempenho.

💡 **Dica:** Para melhorar a acessibilidade, evite usar imagens que contenham texto importante - ou se for inevitável, certifique-se de que o texto também esteja disponível no atributo `alt`! ♿

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/>