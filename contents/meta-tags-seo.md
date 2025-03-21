<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 🔍 **Meta Tags e SEO**

As Meta Tags são fundamentais para otimizar seu site para mecanismos de busca (SEO) e melhorar a experiência do usuário. Elas fornecem informações sobre o documento HTML aos navegadores e motores de busca.

## 📌 **Meta Tags Essenciais**

Estas tags devem estar sempre presentes na seção `<head>` do seu documento HTML:

```html
<head>
    <!-- Define o conjunto de caracteres -->
    <meta charset="UTF-8">
    
    <!-- Configuração de viewport para responsividade -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Título da página (crucial para SEO) -->
    <title>Título Otimizado da Página | Nome do Site</title>
    
    <!-- Descrição da página (aparece nos resultados de busca) -->
    <meta name="description" content="Uma descrição concisa e atrativa da página com 150-160 caracteres, incluindo palavras-chave relevantes.">
    
    <!-- Palavras-chave (menos importante hoje, mas ainda usado) -->
    <meta name="keywords" content="html, meta tags, seo, otimização">
    
    <!-- Autor da página -->
    <meta name="author" content="Seu Nome">
</head>
```

## 🌐 **Meta Tags para Redes Sociais**

### **Open Graph (Facebook, LinkedIn)**

```html
<meta property="og:title" content="Título para Compartilhamento">
<meta property="og:description" content="Descrição atrativa para compartilhamento em redes sociais.">
<meta property="og:image" content="https://www.seusite.com/imagem-compartilhamento.jpg">
<meta property="og:url" content="https://www.seusite.com/pagina">
<meta property="og:type" content="website">
<meta property="og:site_name" content="Nome do Seu Site">
```

### **Twitter Card**

```html
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@seuhandle">
<meta name="twitter:title" content="Título para Twitter">
<meta name="twitter:description" content="Descrição para compartilhamento no Twitter.">
<meta name="twitter:image" content="https://www.seusite.com/imagem-twitter.jpg">
```

## 🔒 **Segurança e Indexação**

```html
<!-- Instruções para robôs de busca -->
<meta name="robots" content="index, follow">
<!-- Alternativas: noindex, nofollow, none, noarchive -->

<!-- Política de referenciador -->
<meta name="referrer" content="no-referrer-when-downgrade">

<!-- Segurança -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
```

## 🔄 **Redirecionamento**

```html
<!-- Redireciona após 5 segundos -->
<meta http-equiv="refresh" content="5;url=https://www.novapagina.com">
```

## 🎨 **Tema e Aparência**

```html
<!-- Cor da barra de endereço em dispositivos móveis -->
<meta name="theme-color" content="#4285f4">

<!-- Status bar no iOS -->
<meta name="apple-mobile-web-app-status-bar-style" content="black">

<!-- Ícones -->
<link rel="icon" href="favicon.ico">
<link rel="apple-touch-icon" href="apple-touch-icon.png">
```

## 📱 **Web App Manifest**

```html
<!-- Para sites progressivos (PWA) -->
<link rel="manifest" href="/manifest.json">
```

## 💡 **Canonical URL**

```html
<!-- Define a URL canônica para evitar conteúdo duplicado -->
<link rel="canonical" href="https://www.seusite.com/pagina-original">
```

## 📝 **Exemplo Completo**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia HTML: Meta Tags e SEO | GuiaHTML</title>
    <meta name="description" content="Aprenda sobre meta tags e como otimizar seu site para mecanismos de busca (SEO) com o GuiaHTML.">
    <meta name="keywords" content="html, meta tags, seo, otimização, open graph">
    <meta name="author" content="GuiaHTML">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.guiahtml.com/meta-tags-seo">
    <meta property="og:title" content="Guia Completo de Meta Tags e SEO">
    <meta property="og:description" content="Aprenda como as meta tags podem melhorar o SEO do seu site.">
    <meta property="og:image" content="https://www.guiahtml.com/imagens/meta-tags-seo.jpg">
    
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@guiahtml">
    <meta name="twitter:title" content="Guia Completo de Meta Tags e SEO">
    <meta name="twitter:description" content="Aprenda como as meta tags podem melhorar o SEO do seu site.">
    <meta name="twitter:image" content="https://www.guiahtml.com/imagens/meta-tags-seo.jpg">
    
    <!-- Robots -->
    <meta name="robots" content="index, follow">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://www.guiahtml.com/meta-tags-seo">
    
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="favicon.png">
</head>
<body>
    <!-- Conteúdo da página -->
</body>
</html>
```

### 📌 **Boas Práticas de SEO**

✅ Use títulos descritivos e únicos em cada página.  
✅ Escreva descrições meta atraentes com 150-160 caracteres.  
✅ Inclua a palavra-chave principal no título e na descrição.  
✅ Use URLs amigáveis e descritivas.  
✅ Implemente tags Open Graph para compartilhamento em redes sociais.  
✅ Defina uma URL canônica para evitar conteúdo duplicado.  
✅ Use headings (`<h1>` a `<h6>`) de forma hierárquica.  
✅ Otimize imagens com atributos `alt` descritivos.

💡 **Dica:** Os motores de busca modernos valorizam conteúdo de qualidade e experiência do usuário mais do que meta tags. Use as meta tags para complementar seu bom conteúdo, não como substituto! 🚀

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/> 