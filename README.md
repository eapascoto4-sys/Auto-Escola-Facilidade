# Auto Escola Facilidade

Site institucional estático e leve para a Auto Escola Facilidade.

## Arquivos

- `index.html`: conteúdo e estrutura das seções.
- `styles.css`: visual, responsividade e animações.
- `script.js`: menu mobile, header, reveal e efeito leve do hero.
- `logo-auto-escola-facilidade.jpeg`: logo usada no site.

## Rodar localmente

```bash
python3 -m http.server 8000
```

Acesse `http://localhost:8000`.

## Publicar na Vercel

Use estas configurações no projeto da Vercel:

- Framework Preset: `Other`
- Build Command: `npm run build`
- Output Directory: `dist`
- Install Command: vazio ou padrão
- Root Directory: a pasta onde está o `index.html`

Se o repositório tiver o site dentro de uma subpasta, ajuste o `Root Directory` para essa subpasta. Se a Vercel apontar para a pasta errada, ela mostra `404: NOT_FOUND`.

## Editar

- Logo: substitua `logo-auto-escola-facilidade.jpeg`.
- Telefone e WhatsApp: procure por `+55 61 98228-4085`, `tel:+5561982284085` e `https://wa.me/5561982284085` em `index.html`.
- Avaliações: edite a seção `#avaliacoes` em `index.html`. Os textos atuais são placeholders e devem ser substituídos por avaliações reais antes de publicar.
- Cores, espaçamentos e animações: edite `styles.css`.

O site é informativo e não inclui checkout, carrinho, endereço, CNPJ ou redes sociais.
