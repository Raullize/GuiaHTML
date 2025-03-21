<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 📑 **Formulários**

Formulários são elementos essenciais para coletar dados dos usuários. Eles são criados com a tag `<form>` e podem conter vários tipos de campos de entrada.

## 🔍 **Estrutura Básica**

```html
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <button type="submit">Enviar</button>
</form>
```

## 📋 **Principais Elementos de Formulário**

| Elemento | Descrição |
|----------|-----------|
| `<form>` | Container principal que define um formulário |
| `<input>` | Campo de entrada de dados (vários tipos) |
| `<label>` | Rótulo para um campo de entrada |
| `<select>` | Lista suspensa de opções |
| `<textarea>` | Campo para texto multilinha |
| `<button>` | Botão para submeter ou resetar formulário |
| `<fieldset>` | Agrupa elementos relacionados |
| `<legend>` | Título para um `<fieldset>` |

## 🔢 **Tipos de Input (type)**

```html
<!-- Texto simples -->
<input type="text" name="nome">

<!-- Email -->
<input type="email" name="email">

<!-- Senha -->
<input type="password" name="senha">

<!-- Número -->
<input type="number" name="idade" min="18" max="100">

<!-- Data -->
<input type="date" name="nascimento">

<!-- Checkbox -->
<input type="checkbox" name="aceito" id="aceito">
<label for="aceito">Aceito os termos</label>

<!-- Radio button -->
<input type="radio" name="genero" id="masculino" value="M">
<label for="masculino">Masculino</label>
<input type="radio" name="genero" id="feminino" value="F">
<label for="feminino">Feminino</label>

<!-- Arquivo -->
<input type="file" name="documento">

<!-- Cor -->
<input type="color" name="cor">

<!-- Range (slider) -->
<input type="range" name="volume" min="0" max="100">
```

## 📝 **Atributos Importantes**

| Atributo | Descrição |
|----------|-----------|
| `required` | Marca o campo como obrigatório |
| `placeholder` | Texto de exemplo dentro do campo |
| `value` | Valor inicial do campo |
| `disabled` | Desativa o campo |
| `readonly` | Torna o campo somente leitura |
| `min`/`max` | Define valores mínimos/máximos |
| `pattern` | Expressão regular para validação |
| `autocomplete` | Controla preenchimento automático |

### 📌 **Boas Práticas**

✅ Sempre associe `<label>` aos campos usando atributos `for` e `id`.  
✅ Utilize validação tanto no cliente quanto no servidor.  
✅ Agrupe campos relacionados com `<fieldset>`.  
✅ Forneça feedback claro sobre erros de validação.  
✅ Utilize atributos `autocomplete` para melhorar a experiência do usuário.

💡 **Dica:** O atributo `method="post"` é mais seguro para enviar dados sensíveis, enquanto `method="get"` é útil quando você quer que a URL seja compartilhável! 🔒

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/>