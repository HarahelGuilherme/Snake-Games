# Arena Snake

Jogo de cobra em HTML, CSS e JavaScript puro, pensado para rodar em hospedagens estáticas como GitHub Pages e Vercel.

## Como rodar localmente

Abra o arquivo `snake.html` no navegador ou use um servidor local simples:

```bash
python -m http.server 8000
```

Depois abra:

```text
http://localhost:8000/
```

## Como publicar no Vercel

1. Faça upload desta pasta para um repositório GitHub.
2. Conecte o repositório ao Vercel.
3. O Vercel detecta automaticamente os arquivos estáticos.
4. O projeto será servido em uma URL pública.

## Arquivos principais

- `snake.html` — jogo principal
- `index.html` — página de entrada / redirecionamento
- `vercel.json` — configuração do deploy

## Controles

- Mouse: mover a cobra
- Clique/Barra de espaço: turbo

## Observações

- Sem backend
- Sem dependências externas
- Compatível com deploy em páginas estáticas
