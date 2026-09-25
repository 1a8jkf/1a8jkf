# Contador com os bots

O tema precisa de um PNG por dígito (0 a 9). Da sua imagem saíram só 0, 1, 5, 6 e 7,
que já estão em `theme-bots/`. Faltam **2, 3, 4, 8 e 9**.

## 1. Gerar os dígitos que faltam

Prompt para o ChatGPT (mesma conversa da imagem original, se possível):

> Same pixel-art robot mascot style as the previous image, solid pure black background (#000000).
> Create 5 NEW robots, each with a different design from the previous ones, standing full-body on the
> same ground line, each holding a white square sign with one large pixel-font digit: 2, 3, 4, 8 and 9.
> Same size and framing as before, with clear space between the robots so they do not touch or overlap.

Manda a imagem aqui na conversa que eu recorto e salvo como `2.png`, `3.png`, `4.png`, `8.png`, `9.png`
com fundo transparente e todos apoiados na mesma linha do chão.

## 2. Hospedar o contador

```bash
cd counter
docker compose up -d
# teste: http://localhost:3000/@teste?theme=bots
```

Coloque atrás do seu Nginx/Cloudflare com HTTPS. Se o tema não aparecer, compare com a estrutura
de uma pasta existente em `assets/theme` do repositório journey-ad/Moe-Counter.

Alternativa sem servidor próprio: abrir um pedido de tema no repositório journey-ad/Moe-Counter
(aceita contribuições de temas), para usar a instância pública `count.getloli.com`.

## 3. Ligar no README

No bloco `stats` do README, troque `YOUR-COUNTER-HOST` pelo seu domínio e remova os marcadores
`<!--` e `-->` em volta da imagem do contador. O parâmetro `scale` (0.9 no README) ajusta a largura.

`extras/` tem os outros dois bots que seguravam o "0". O contador usa uma imagem por dígito,
então só um deles entra no tema.
