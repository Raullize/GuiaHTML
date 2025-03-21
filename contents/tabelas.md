<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 📊 **Tabelas**

Tabelas HTML são usadas para organizar dados em linhas e colunas, facilitando a visualização de informações tabulares. Embora não devam ser usadas para layout de página, são essenciais para apresentar dados estruturados.

## 🔍 **Estrutura Básica**

```html
<table>
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
            <th>Profissão</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Maria</td>
            <td>25</td>
            <td>Desenvolvedora</td>
        </tr>
        <tr>
            <td>João</td>
            <td>30</td>
            <td>Designer</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">Total: 2 pessoas</td>
        </tr>
    </tfoot>
</table>
```

## 📋 **Principais Elementos**

| Elemento | Descrição |
|----------|-----------|
| `<table>` | Define uma tabela |
| `<thead>` | Agrupa o conteúdo do cabeçalho |
| `<tbody>` | Agrupa o conteúdo principal da tabela |
| `<tfoot>` | Agrupa o conteúdo do rodapé |
| `<tr>` | Define uma linha da tabela |
| `<th>` | Define uma célula de cabeçalho |
| `<td>` | Define uma célula de dados |
| `<caption>` | Adiciona um título/legenda à tabela |

## 🛠️ **Atributos Úteis**

### Mesclar Células
```html
<!-- Mesclar colunas -->
<td colspan="2">Célula que ocupa duas colunas</td>

<!-- Mesclar linhas -->
<td rowspan="3">Célula que ocupa três linhas</td>
```

### Alinhamento e Estilo
```html
<table border="1" cellspacing="0" cellpadding="10">
    <!-- Conteúdo da tabela -->
</table>
```

> ⚠️ **Nota:** Os atributos `border`, `cellspacing` e `cellpadding` são considerados obsoletos no HTML5. Recomenda-se usar CSS para estilização.

## 🎨 **Estilizando com CSS**

```css
table {
    border-collapse: collapse;
    width: 100%;
}

th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
    font-weight: bold;
}

tr:nth-child(even) {
    background-color: #f9f9f9;
}
```

## 🔄 **Tabelas Responsivas**

Para tornar tabelas responsivas em dispositivos móveis, envolva-as em um contêiner com overflow:

```html
<div style="overflow-x: auto;">
    <table>
        <!-- Conteúdo da tabela -->
    </table>
</div>
```

### 📌 **Boas Práticas**

✅ Use `<thead>`, `<tbody>` e `<tfoot>` para melhor organização semântica.  
✅ Adicione `<caption>` para descrever o conteúdo da tabela.  
✅ Utilize o atributo `scope` nos elementos `<th>` para melhorar a acessibilidade.  
✅ Evite tabelas muito complexas - considere dividir em múltiplas tabelas se necessário.  
✅ Não use tabelas para layout - utilize CSS Flexbox ou Grid.

💡 **Dica:** Para melhorar a acessibilidade, use o atributo `headers` nas células `<td>` e `id` nas células `<th>` para associá-las! ♿

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/>