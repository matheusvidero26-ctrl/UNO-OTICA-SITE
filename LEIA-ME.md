# Uno Óticas — landing page (base: demo Grau)

## Rodar
```
npm i
npm run dev      # abre em http://localhost:5181
npm run build    # gera dist/ para subir na hospedagem (Vercel, Netlify, Hostinger)
```
Precisa de Node 18+ e internet no `npm i` (three, gsap, lenis, optician-sans, vite).

## O que já é da Uno
- Cor: fundo laranja da marca (#f06c2a na tela; o WebGL desenha #fe783c porque o mapeamento de tons escurece um pouco), texto branco; o trecho de sol e o do processo continuam em papel claro.
- Logo: "UNO" desenhado em traço (loader, nav, rodapé, favicon) + "ÓTICAS" fino; "UNO ÓTICAS" na tampa do estojo, com feltro laranja.
- Fonte: Montserrat (OFL, em `public/fonts/`), a mais próxima do logo. A Satoshi da demo saiu.
- Textos tirados do Instagram @unooticas (set–out/2026) e do Google: exame de vista gratuito, Varilux / Crizal / Transitions, solar com grau, parcelamento em até 12x, envio para todo o Brasil, nota 4,9 (106 avaliações), endereços das lojas.
- Formulário: escolhe a loja (6 unidades) e o período e abre o WhatsApp daquela loja com a mensagem pronta para agendar o exame.

## O que ainda é da demo / falta mandar
1. **Fotos**: os 4 cartões das lentes, a praia e as 4 fotos do processo são da demo (`public/img/`). Trocar por fotos das lojas Uno (lentes e praia: 3:2, 1536 px+, sem texto; processo: 2:3 e 3:2, 1024 px+).
2. **Modelos e preços das armações**: Quadrada, Gatinho, Aviador e Redonda são da demo; o preço virou "Parcela em até 12x".
3. **Horários de cada loja** (só o horário de exame está no Instagram) e o **endereço da Vila Formosa**.
4. **CNPJ** para a linha legal.
5. **Promoção atual**: as do Instagram (aniversário, Varilux até 09/10, Outubro Rosa) já venceram, então ficaram fora. Mande a de agora que eu encaixo.
6. Frases técnicas das lentes (visão simples, multifocal, antirreflexo, lente fina) são genéricas: conferir com a loja.

O guia técnico completo do projeto está em `CLAUDE.md` (seção "Personalizar").
