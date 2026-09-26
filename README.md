# Escala Comercial Previsível — Landing page lowticket

Página de vendas do kit **Escala Comercial Previsível** (P4 Gestão), baseada na estrutura da página do MPE Digital, com a paleta azul P4.

- **URL final:** https://gec.p4gestao.com.br/
- **Checkout:** https://pay.hotmart.com/C107767987J
- **Meta Pixels:** 1427020837779378 + 3103391829973250 · **Clarity:** sn3gbc8rkb (mesmos do MPE — trocar o Clarity se criar um projeto novo)
- **Preço:** 8x R$ 9,70 ou R$ 67 à vista · pagamento único · garantia 7 dias

## Pendências da v1
1. Mockups provisórios feitos em CSS (hero, dobra "entrega" e oferta). Substituir por `assets/mockup-dobra1.png`, `assets/mockup-dobra5.png` e `assets/mockup-oferta.png` — os pontos estão marcados no HTML com o comentário `MOCKUP PROVISÓRIO`.

## Publicar no GitHub Pages
1. Crie um repositório público e suba o **conteúdo** desta pasta na raiz.
2. Settings → Pages → Source: branch `main`, pasta `/ (root)`.
3. Cloudflare: CNAME `gec` → `SEU_USUARIO.github.io`, em **DNS only** (nuvem cinza).
4. Settings → Pages → Custom domain: `gec.p4gestao.com.br`. Aguarde "DNS check successful".
5. Marque **Enforce HTTPS**.

> A API de Conversões (CAPI) da Meta é configurada no painel da Hotmart, nunca no HTML.

## NÃO subir para o GitHub
- `assets/mockup-dobra1-original.png` (backup em alta)
- `assets/mockup-dobra1.webp` (sobra de teste)
- `.DS_Store`
