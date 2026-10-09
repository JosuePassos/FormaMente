# FormaMente

Catálogo estático e responsivo para apresentar produtos, filtrar itens e iniciar pedidos pelo WhatsApp. O projeto usa HTML, CSS e JavaScript puro, sem etapa de compilação.

## Estrutura

```text
FormaMente/
├── index.html     # Estrutura da página e navegação
├── style.css      # Cores, tipografia, layout e adaptação para celular
├── script.js      # Produtos, filtros e pedidos pelo WhatsApp
├── assets/        # Fotos, logo e outros arquivos visuais
└── README.md      # Descrição e instruções do projeto
```

## Executar localmente

Abra `index.html` no navegador. Para usar um servidor local, execute na pasta do projeto:

```sh
python -m http.server 8000
```

Depois, acesse <http://localhost:8000>.

## Personalizar

- Em `script.js`, substitua os produtos de exemplo na lista `products` pelos seus itens. Cada produto tem `id`, `name`, `category`, `description` e `price`.
- Defina `WHATSAPP_PHONE` com o número de atendimento no formato internacional, somente dígitos, incluindo o código do país e o DDD. Exemplo: `"5511999999999"`. O número está vazio de propósito até você configurá-lo.
- Adicione fotos e o logotipo em `assets/` e atualize o HTML/CSS para usá-los.
- Atualize nome, textos, cores e informações de contato conforme a identidade do projeto.

Os produtos e preços exibidos inicialmente são apenas exemplos; troque-os antes de divulgar o catálogo.