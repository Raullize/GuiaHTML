<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 🏷️ **Atributos de Dados (data-*)**

Os atributos de dados HTML (`data-*`) são atributos personalizados que permitem armazenar informações extras diretamente nos elementos HTML. Introduzidos no HTML5, eles oferecem uma maneira padrão de adicionar dados próprios aos elementos.

## 🔍 **O que são Atributos data-\***

Os atributos de dados são atributos personalizados que começam obrigatoriamente com o prefixo `data-` seguido pelo nome que você desejar.

```html
<article
  id="eletronicos"
  data-categoria="tecnologia"
  data-data-publicacao="2023-05-15"
  data-autor="maria.silva">
  
  <h2>Novos Dispositivos de 2023</h2>
  <p>Conteúdo do artigo aqui...</p>
</article>
```

## 📋 **Regras para Atributos data-\***

Ao criar atributos de dados, siga estas regras:

1. Sempre comece com o prefixo `data-`
2. Pelo menos um caractere após o prefixo
3. Apenas letras minúsculas, números, hífens, pontos, dois pontos ou sublinhados
4. Não deve conter letras maiúsculas (recomendação HTML5)
5. Pode armazenar qualquer string como valor

## 🧩 **Exemplos de Uso no HTML**

### **Exemplo 1: Cartões de Produto**

```html
<div class="produto" 
     data-id="1234" 
     data-nome="Smartphone Pro Max" 
     data-preco="1999.99"
     data-disponivel="true"
     data-cores="preto,branco,azul">
  <h3>Smartphone Pro Max</h3>
  <p>R$ 1.999,99</p>
  <button>Comprar</button>
</div>
```

### **Exemplo 2: Navegação em Abas**

```html
<div class="abas">
  <button data-aba-alvo="aba1" data-ativo="true">Informações</button>
  <button data-aba-alvo="aba2" data-ativo="false">Especificações</button>
  <button data-aba-alvo="aba3" data-ativo="false">Avaliações</button>
</div>

<div id="aba1" class="conteudo-aba">
  Informações do produto aqui...
</div>
<div id="aba2" class="conteudo-aba" hidden>
  Especificações técnicas aqui...
</div>
<div id="aba3" class="conteudo-aba" hidden>
  Avaliações de clientes aqui...
</div>
```

### **Exemplo 3: Galeria de Imagens**

```html
<div class="galeria">
  <img src="foto1.jpg" 
       data-tipo="paisagem" 
       data-local="montanhas" 
       data-data="2023-01-15" 
       data-fotografo="joão.silva"
       data-descricao="Vista do nascer do sol nas montanhas">
       
  <img src="foto2.jpg"
       data-tipo="retrato"
       data-local="estúdio"
       data-data="2023-02-10"
       data-fotografo="maria.santos"
       data-descricao="Retrato profissional em fundo branco">
</div>
```

### **Exemplo 4: Dados para Tradução**

```html
<p data-traducao-chave="bem-vindo">Bem-vindo ao nosso site!</p>
<button data-traducao-chave="continuar">Continuar</button>
<span data-traducao-chave="copyright">Todos os direitos reservados</span>
```

## 🎨 **Estilizando com Atributos de Dados**

Os atributos de dados podem ser utilizados como seletores CSS:

```html
<ul>
  <li data-importancia="alta">Finalizar relatório</li>
  <li data-importancia="media">Responder emails</li>
  <li data-importancia="baixa">Organizar arquivos</li>
</ul>
```

```css
/* Estilo para itens baseado no valor do atributo data-* */
[data-importancia="alta"] {
  color: red;
  font-weight: bold;
}

[data-importancia="media"] {
  color: orange;
}

[data-importancia="baixa"] {
  color: green;
}

/* Selecionando elementos que possuem qualquer valor para o atributo */
[data-traducao-chave] {
  font-style: italic;
}

/* Selecionando elementos cujo atributo começa com determinado valor */
[data-local^="mont"] {
  border: 1px solid blue;
}

/* Selecionando elementos cujo atributo termina com determinado valor */
[data-fotografo$="silva"] {
  border-bottom: 2px dotted gray;
}

/* Selecionando elementos cujo atributo contém determinado valor */
[data-cores*="azul"] {
  background-color: lightblue;
}
```

## 📏 **Benefícios e Casos de Uso**

1. **Armazenar Metadados**
   - Guardar informações sobre um elemento que não são visíveis diretamente
   - Exemplo: categorias, datas, status, IDs de referência

2. **Configuração de Componentes**
   - Definir comportamentos ou propriedades de componentes HTML
   - Exemplo: opções de carregamento, parâmetros de configuração

3. **Filtragem e Ordenação**
   - Facilitar sistemas de filtragem e ordenação de elementos
   - Exemplo: galerias filtráveis, listas ordenáveis

4. **Manter Relacionamentos**
   - Estabelecer relações entre elementos em uma página
   - Exemplo: conectar rótulos e conteúdos, itens relacionados

5. **Internacionalização**
   - Armazenar chaves de tradução para múltiplos idiomas
   - Exemplo: marcadores para sistemas de tradução dinâmica

### 📌 **Boas Práticas**

✅ Use nomes descritivos e bem organizados para seus atributos de dados.  
✅ Utilize atributos de dados para informações específicas do elemento.  
✅ Prefira atributos HTML padrão quando disponíveis (`alt`, `title`, etc).  
✅ Mantenha os valores simples e previsíveis.  
✅ Documente os atributos personalizados usados em seu projeto.  
✅ Use hífens para separar palavras em nomes compostos (`data-nome-completo` vs `data-nomecompleto`).

💡 **Dica:** Os atributos `data-*` são uma excelente forma de adicionar informações extras aos elementos HTML sem comprometer a validade do seu código ou recorrer a propriedades não padronizadas!

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/> 