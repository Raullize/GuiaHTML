<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 🎮 **Atributos de Eventos HTML**

Os atributos de eventos HTML permitem adicionar interatividade aos elementos da página. Estes atributos especiais começam com "on" e são uma parte fundamental do HTML para conectar a estrutura da página com comportamentos interativos.

## 🔍 **Sintaxe dos Atributos de Eventos**

Os atributos de eventos são adicionados diretamente às tags HTML:

```html
<button onclick="alert('Botão clicado!')">Clique em mim</button>
```

## 📋 **Principais Atributos de Eventos**

### **Eventos de Mouse**

| Atributo | Descrição |
|----------|-----------|
| `onclick` | Acionado quando o elemento é clicado |
| `ondblclick` | Acionado quando o elemento recebe um duplo clique |
| `onmouseover` | Acionado quando o cursor passa sobre o elemento |
| `onmouseout` | Acionado quando o cursor sai do elemento |
| `onmousedown` | Acionado quando o botão do mouse é pressionado sobre o elemento |
| `onmouseup` | Acionado quando o botão do mouse é liberado sobre o elemento |

### **Eventos de Teclado**

| Atributo | Descrição |
|----------|-----------|
| `onkeydown` | Acionado quando uma tecla é pressionada |
| `onkeyup` | Acionado quando uma tecla é liberada |
| `onkeypress` | Acionado quando uma tecla é pressionada e depois liberada |

### **Eventos de Formulário**

| Atributo | Descrição |
|----------|-----------|
| `onsubmit` | Acionado quando um formulário é enviado |
| `onreset` | Acionado quando um formulário é resetado |
| `onchange` | Acionado quando o valor de um elemento muda |
| `onfocus` | Acionado quando um elemento recebe foco |
| `onblur` | Acionado quando um elemento perde foco |
| `oninput` | Acionado quando um usuário insere um valor |

### **Eventos de Documento/Janela**

| Atributo | Descrição |
|----------|-----------|
| `onload` | Acionado quando a página termina de carregar |
| `onresize` | Acionado quando a janela é redimensionada |
| `onscroll` | Acionado quando a barra de rolagem é movida |
| `onerror` | Acionado quando ocorre um erro de carregamento |

## 🖼️ **Exemplos de Uso**

### **Botão Simples**
```html
<button onclick="alert('Olá, mundo!')">Diga Olá</button>
```

### **Formulário com Validação**
```html
<form onsubmit="return confirmarEnvio()">
  <input type="text" id="nome" required>
  <button type="submit">Enviar</button>
</form>
```

### **Entrada com Feedback**
```html
<input type="text" 
       onfocus="this.style.backgroundColor='lightyellow'" 
       onblur="this.style.backgroundColor='white'">
```

### **Imagem com Tratamento de Erro**
```html
<img src="imagem.jpg" 
     alt="Minha imagem" 
     onerror="this.src='imagem-alternativa.jpg'">
```

## 📌 **Boas Práticas**

✅ Mantenha o código dentro dos atributos de eventos o mais simples possível.  
✅ Para lógica complexa, prefira referenciar funções ao invés de incluir todo o código no atributo.  
✅ Considere a acessibilidade ao implementar interações baseadas em eventos.  
✅ Lembre-se que o HTML é para estrutura, então é recomendável separar comportamentos complexos em arquivos JavaScript separados.

💡 **Dica:** Os atributos de eventos HTML são parte do padrão HTML e funcionam sem bibliotecas JavaScript adicionais, tornando-os úteis para interações simples e diretas!

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/> 