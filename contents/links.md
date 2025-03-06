<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=header"/>

# 🔗 **Links**

Links são elementos essenciais em HTML, permitindo a navegação entre páginas e recursos na web. Eles são criados usando a tag `<a>` (âncora) e podem ser configurados com URLs **absolutos** ou **relativos**, dependendo da necessidade.

## Criando links com `<a>`:

```html
<a href="https://www.google.com" target="_blank" rel="noopener noreferrer">Visite o Google</a>
```

### **URL Absoluto vs. URL Relativo**

#### 1. **URL Absoluto**:
- Um URL absoluto contém o endereço completo do recurso, incluindo o protocolo (`http://` ou `https://`), o domínio e o caminho completo.
- É usado para links que apontam para páginas ou recursos fora do site atual.
- Exemplo:
  ```html
  <a href="https://www.exemplo.com/sobre">Sobre Nós</a>
  ```
  - Esse link aponta para a página "Sobre Nós" no site `www.exemplo.com`.

#### 2. **URL Relativo**:
- Um URL relativo define o caminho do recurso em relação à localização atual do arquivo.
- É usado para links que apontam para páginas ou recursos dentro do mesmo site ou projeto.
- Exemplos:
  - **Mesmo diretório**:
    ```html
    <a href="contato.html">Página de Contato</a>
    ```
    - Esse link aponta para o arquivo `contato.html` que está na mesma pasta do arquivo atual.

  - **Subdiretório**:
    ```html
    <a href="blog/post1.html">Post 1</a>
    ```
    - Esse link aponta para o arquivo `post1.html` dentro da pasta `blog`.

  - **Diretório anterior**:
    ```html
    <a href="../sobre.html">Sobre</a>
    ```
    - O `../` indica que o arquivo `sobre.html` está em uma pasta acima da pasta atual.

  - **Raiz do site**:
    ```html
    <a href="/imagens/logo.png">Ver Logo</a>
    ```
    - O `/` no início indica que o caminho começa na raiz do site, independentemente da localização atual.

---

### **Atributos importantes para links**:

1. **`href`**:
   - Define o destino do link. Pode ser um URL absoluto ou relativo.
   - Exemplo:
     ```html
     <a href="https://www.exemplo.com">URL Absoluto</a>
     <a href="contato.html">URL Relativo</a>
     ```

2. **`target`**:
   - Especifica onde o link será aberto. Valores comuns:
     - `_blank`: Abre em uma nova aba.
     - `_self`: Abre na mesma aba (padrão).
   - Exemplo:
     ```html
     <a href="https://www.exemplo.com" target="_blank">Abrir em nova aba</a>
     ```

3. **`rel`**:
   - Define a relação entre o documento atual e o link. Valores comuns:
     - `noopener`: Previne que a nova aba acesse a janela original.
     - `noreferrer`: Oculta a informação de referência.
   - Exemplo:
     ```html
     <a href="https://www.exemplo.com" rel="noopener noreferrer">Link seguro</a>
     ```

4. **`title`**:
   - Adiciona uma dica (tooltip) ao link, exibindo um texto quando o usuário passa o mouse sobre ele.
   - Exemplo:
     ```html
     <a href="https://www.exemplo.com" title="Visite o site Exemplo">Exemplo</a>
     ```

5. **`download`**:
   - Indica que o link deve ser baixado ao invés de navegado.
   - Exemplo:
     ```html
     <a href="arquivo.pdf" download>Baixar PDF</a>
     ```

---

[🔙 Voltar ao índice principal](../README.md)

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=E34F26&height=120&section=footer"/>