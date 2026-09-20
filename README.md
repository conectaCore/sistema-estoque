# EstoquePro — GitHub Pages

Sistema estático de controle de estoque, vendas e caixa.

## Como publicar

1. Crie um repositório no GitHub.
2. Coloque `index.html` na raiz do repositório.
3. Envie as pastas `assets/css` e `assets/js`.
4. No GitHub: **Settings → Pages**.
5. Em **Build and deployment**, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Salve e aguarde a publicação.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- Lucide Icons
- localStorage

## Observação importante

GitHub Pages é hospedagem estática. Não existe PHP/MySQL executando no GitHub Pages.

Nesta versão os dados ficam no `localStorage` do navegador. Portanto, dois computadores podem ter estoques diferentes.

Para transformar em sistema multiusuário no futuro, a interface pode ser mantida e o JavaScript pode passar a consumir uma API PHP/MySQL, Supabase, Firebase ou outro backend.

## Comprovante

A opção de venda gera um comprovante de controle interno que pode ser impresso ou salvo como PDF pelo navegador. Ele não é uma NF-e/NFC-e fiscal.
