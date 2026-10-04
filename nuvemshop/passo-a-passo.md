# Ordiné na Nuvemshop — passo a passo

Base: documento "Ordiné — contexto da marca e do site" (Drive) e a planilha de pedido.
Os nomes dos menus podem variar um pouco no painel; se algum não bater, procure pelo equivalente.
Itens em [colchetes] ainda precisam de decisão sua.

## 1. Importar os produtos
Arquivo: `nuvemshop/produtos-ordine.csv` (7 produtos, 68 variações, 81 peças).

1. Painel → **Produtos** → **Importar** (ou Importar/Exportar planilha).
2. Suba o CSV e conclua a importação.
3. Confira: cada produto com as variações Cor e Tamanho agrupadas, preço, estoque, peso e medidas da caixa (15×30×30 cm).
4. Categorias: confirme que "Coleção 01" e as subcategorias (Tops, Croppeds, Shorts, Calças) foram criadas.
5. Os produtos estão como "Visível". Se quiser esconder até o lançamento (15/10), mude a visibilidade antes.
6. Fotos: envie por produto (luz natural, tons neutros quentes, pouco texto sobre a imagem).

## 2. Tema, cores e fonte
1. **Design → Temas**: aplique o tema **Morelia** (era a ideia inicial o Rio; o documento escolheu Morelia).
2. **Design → Personalizar** (editor visual) → Cores. Valores sugeridos, ainda não confirmados:

| Uso | Cor | Hex |
|---|---|---|
| Fundo | Off-White | #F5F1EA |
| Seções alternadas | Areia | #E4D9C7 |
| Detalhes, bordas | Greige | #B8AD9C |
| Texto secundário | Chocolate | #4A3B2F |
| Texto principal, botões | Preto Suave | #2B2622 |
| Acento (preços, destaques) | Rosé | #D9B8AC |

3. **Fontes**: títulos em Cormorant Garamond; corpo em Montserrat ou Poppins (escolha uma). Se o tema só oferecer fontes da lista dele, escolha a serifada mais próxima e anote para ajustar depois.
4. **Logo**: envie o logo com a flor de cinco pétalas e o favicon.

## 3. Home
- **Banner**: "existe beleza no ordinário." / "Ordiné — roupas pra se mover como você é, todo dia." Botão: "Ver coleção" (link para a categoria Coleção 01).
- **Manifesto curto**: "A gente não acredita em dias perfeitos. Acredita nos dias comuns — o treino de terça, o café corrido, o momento sozinha antes de todo mundo acordar. É no ordinário que a beleza mora de verdade. Por isso a Ordiné nasceu: peças pensadas pra acompanhar sua rotina real, com conforto e caimento que fazem sentido no seu dia, não só na foto."
- **Destaque da coleção**: "Coleção 01 — sete peças, um propósito: vestir o ordinário com leveza." Botão: "Conferir peças".
- **Fecho**: "Feito com cuidado, do tecido ao acabamento. Uma marca pequena, pensada grande."
- Regra do tom: o site fala do propósito; não apresenta Quezia e Jean por enquanto.

## 4. Páginas
**Sobre** (Páginas → Nova página):
"existe beleza no ordinário. Ordiné nasceu de uma ideia simples: a vida real acontece nos dias comuns, não nos momentos de destaque. É no treino de segunda, no café tomado correndo, na rotina que se repete — e que, mesmo assim, tem beleza. O nome vem de 'ordinário', não no sentido de sem graça, mas no sentido mais bonito da palavra: aquilo que é comum, cotidiano, de todo dia. Nossas peças acompanham esse cotidiano com conforto, caimento e qualidade, do treino ao dia a dia, sem cerimônia. A flor de cinco pétalas é o símbolo: delicada, mas resistente."

**Categoria Coleção 01** (descrição): "A primeira coleção da Ordiné. Sete peças pensadas pra vestir o seu dia comum com conforto de verdade, do treino ao resto da rotina. Tecido leve, caimento que acompanha o movimento, cores que combinam com tudo."

**Contato**: "Dúvidas sobre pedido, troca ou sobre a coleção? Fala com a gente — respondemos rapidinho." Inclua WhatsApp e/ou e-mail [definir].

**Tabela de medidas** (por peça, P/M/G): [medir com a Melfit ou nas peças e preencher].

## 5. Políticas (modelos; complete os campos)
- **Trocas e devoluções**: até [7 ou 30] dias corridos após o recebimento, pelo canal [WhatsApp/e-mail]; peça sem uso, com etiqueta e embalagem originais; frete de volta por conta do cliente, exceto defeito ou erro no envio; reembolso ou nova peça em até [X] dias úteis após recebermos o produto.
- **Envio**: todo o Brasil via [transportadora/Correios]; separação em [X] dias úteis; prazo de entrega calculado pelo CEP; código de rastreio por e-mail.
- **Privacidade**: coletamos só o necessário pra processar o pedido (nome, endereço, contato, pagamento), sem compartilhar com terceiros além de logística e pagamento, conforme a LGPD.

## 6. Rodapé e menu
- Menu principal: Coleção 01, Sobre, Contato.
- Rodapé: Sobre, Trocas e devoluções, Envio, Privacidade, Contato, Instagram @use.ordine e a frase "existe beleza no ordinário."

## 7. FAQ
- Prazo de entrega: varia por CEP.
- Troca de tamanho: sim, dentro da política.
- Numeração em relação a outras marcas: [tabela de medidas].
- Rastreio: por e-mail.

## 8. SEO
| Página | Title | Meta descrição |
|---|---|---|
| Home | Ordiné — existe beleza no ordinário | Roupas fitness pensadas pro seu dia a dia real. Conheça a Coleção 01 da Ordiné. |
| Sobre | Sobre a Ordiné | A história e o propósito por trás da Ordiné: roupas que vestem o cotidiano com beleza. |
| Coleção 01 | Coleção 01 — Ordiné | Tops, croppeds, shorts e calças fitness em tecido leve. Confira a primeira coleção da Ordiné. |
| Contato | Fale com a Ordiné | Dúvidas sobre pedidos, trocas ou a coleção? Fale com a gente. |

Produtos: título "Nome da peça — Ordiné" (já no CSV); URLs curtas sem acento (já no CSV). Alt text das fotos: descreva peça e cor.

## 9. Pagamento, frete e domínio
- **Pagamentos**: ative Pix, cartão e boleto pelo meio de pagamento da Nuvemshop (Pago Nubank ou outro) [escolher]. Exige CNPJ ou CPF conforme o meio.
- **Frete**: configure o cálculo por CEP com [Correios/transportadora]; as medidas e pesos dos produtos já estão no CSV. Defina se haverá frete grátis acima de um valor [definir].
- **Domínio**: use o domínio da Nuvemshop até o lançamento ou conecte um próprio [ex.: useordine.com.br].
- **CNPJ**: ainda não formalizado; confira com o meio de pagamento se aceita CPF no início.

## 10. Antes de publicar (checklist)
- [ ] Produtos importados e conferidos, com fotos
- [ ] Tema, cores, fonte e logo aplicados
- [ ] Home, Sobre, Contato e políticas publicadas
- [ ] Pagamento e frete testados com um pedido de teste
- [ ] Domínio conectado
- [ ] Loja liberada (sem senha) na data do lançamento: 15/10/2026 (10/10 se as peças chegarem antes)
