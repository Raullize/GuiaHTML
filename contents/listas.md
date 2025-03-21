<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 📋 **Listas**

As listas são elementos fundamentais no HTML para organizar informações de forma estruturada. Existem três tipos principais: listas ordenadas, não ordenadas e de definição.

## 📌 **Tipos de Listas**

### 1. **Lista Não Ordenada (`<ul>`)**

Usada quando a ordem dos itens não importa. Por padrão, os itens são marcados com bullets (círculos).

```html
<ul>
    <li>Maçã</li>
    <li>Banana</li>
    <li>Laranja</li>
    <li>Uva</li>
</ul>
```

### 2. **Lista Ordenada (`<ol>`)**

Usada quando a ordem dos itens é importante. Por padrão, os itens são numerados sequencialmente.

```html
<ol>
    <li>Acordar</li>
    <li>Escovar os dentes</li>
    <li>Tomar café da manhã</li>
    <li>Ir trabalhar</li>
</ol>
```

### 3. **Lista de Definição (`<dl>`)**

Usada para apresentar termos e suas definições, como um glossário.

```html
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language - linguagem para estruturar conteúdo web</dd>
    
    <dt>CSS</dt>
    <dd>Cascading Style Sheets - linguagem para estilizar páginas web</dd>
    
    <dt>JavaScript</dt>
    <dd>Linguagem de programação que permite adicionar interatividade às páginas web</dd>
</dl>
```

## 🛠️ **Atributos e Variações**

### **Listas Ordenadas Personalizadas**

```html
<!-- Números romanos maiúsculos -->
<ol type="I">
    <li>Item I</li>
    <li>Item II</li>
</ol>

<!-- Números romanos minúsculos -->
<ol type="i">
    <li>Item i</li>
    <li>Item ii</li>
</ol>

<!-- Letras maiúsculas -->
<ol type="A">
    <li>Item A</li>
    <li>Item B</li>
</ol>

<!-- Letras minúsculas -->
<ol type="a">
    <li>Item a</li>
    <li>Item b</li>
</ol>

<!-- Iniciar com número específico -->
<ol start="5">
    <li>Item 5</li>
    <li>Item 6</li>
</ol>

<!-- Ordem reversa -->
<ol reversed>
    <li>Último item</li>
    <li>Penúltimo item</li>
</ol>
```

### **Listas Não Ordenadas Personalizadas**

A aparência dos marcadores pode ser personalizada com CSS:

```css
ul {
    list-style-type: square; /* quadrado */
}

ul.circle {
    list-style-type: circle; /* círculo vazio */
}

ul.disc {
    list-style-type: disc; /* círculo preenchido (padrão) */
}

ul.custom {
    list-style-image: url('bullet.png'); /* imagem customizada */
}
```

## 🔄 **Listas Aninhadas**

Você pode aninhar listas dentro de outras listas para criar estruturas hierárquicas:

```html
<ul>
    <li>Frutas
        <ul>
            <li>Maçã</li>
            <li>Banana</li>
            <li>Laranja</li>
        </ul>
    </li>
    <li>Legumes
        <ul>
            <li>Cenoura</li>
            <li>Brócolis</li>
            <li>Abóbora</li>
        </ul>
    </li>
</ul>
```

## 📱 **Listas de Navegação**

As listas são frequentemente usadas para criar menus de navegação:

```html
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">Sobre</a></li>
        <li><a href="services.html">Serviços</a></li>
        <li><a href="contact.html">Contato</a></li>
    </ul>
</nav>
```

### 📌 **Boas Práticas**

✅ Use listas ordenadas quando a sequência for importante.  
✅ Use listas não ordenadas para itens sem ordem específica.  
✅ Use listas de definição para termos e suas descrições.  
✅ Utilize CSS para estilizar listas em vez de atributos HTML obsoletos.  
✅ Evite listas muito aninhadas, que podem dificultar a navegação.

💡 **Dica:** Para remover os marcadores de uma lista e criar menus de navegação mais flexíveis, use `list-style: none;` no CSS! 🚀

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/>