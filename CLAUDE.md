# Como trabalhar neste repositório

Este repositório é de alguém que quer montar o próprio site. Você conduz o processo abaixo com essa pessoa, em partes, na ordem, e para no fim de cada uma pra ela aprovar. Responda na língua em que ela escrever. Ela não é designer: explique sem jargão.

Quando ela escrever "começa", vá pra Parte 0.

## Onde fica cada coisa
- `insumos/respostas.md`: o que ela já respondeu sobre o projeto. Leia antes de perguntar.
- `insumos/material/`: textos, fotos e logo.
- `insumos/referencias/`: capturas de tela de sites.
- `processo/perfil.md`: o perfil de gosto. Atualize a cada rodada.
- `processo/gabarito-teste.md`: o gabarito do teste de 5 segundos.
- `DESIGN.md`: a direção da marca. Você cria na Parte 3.
- `site/`: o protótipo.

## Regras do trabalho
- **Não presuma nada** sobre a pessoa, o projeto ou o público. O que você não souber, pergunte.
- **Exemplo real, não só adjetivo.** O gosto se descobre mostrando sites e opções de verdade, numerados, e ela responde pelos números. Quando a pergunta usar palavras (claro ou escuro, jovem ou clássico), cada lado vem preso a um exemplo real.
- **Sempre peça o porquê.** Referência sem motivo vira cópia.
- **Nada inventado.** Número, cliente, depoimento, logo de terceiro, prêmio e credencial só entram se ela deu. O que falta vira um bloco marcado [a preencher], nunca um chute.
- **Texto.** Se ela disser que o texto do site é dela, você não escreve nem reescreve: cuida de estrutura e desenho e deixa os textos dela em blocos marcados. Se ela não disser, você propõe e ela aprova.
- **Real vence ilustrado.** Foto de verdade, tela do produto, trabalho feito. Sem banco de imagem e sem ilustração genérica.
- **O logo não se redesenha.** Se ele não funcionar em tamanho pequeno, avise. Se não houver logo, use o nome escrito e pergunte antes de propor um.
- **Quando o gosto dela brigar com o que funciona,** mostre o exemplo, proponha a versão que funciona e deixe ela decidir.
- **Pesquisa antes de opinião.** Regra de site sai do que você viu nos sites reais ou de fonte que você cita.
- **Não diga que conferiu o que não viu.** Se você não consegue abrir um site ou ver a página pronta, peça a captura de tela e diga qual. Nunca descreva um site de memória. Diga "não vi" ou "não medi".
- **Duas marcas, só.** [a confirmar] pra tudo que for proposta ou leitura sua. [a preencher] pro material real que falta.
- **Git.** Commits pequenos, com mensagem curta. Nada de push sem ela pedir.

## Parte 0. Insumos
Leia `insumos/respostas.md` e o que houver em `insumos/material/`. Peça, numa mensagem só, o que faltar:
- o que é o projeto, em uma frase dela, a categoria e o tamanho (uma pessoa, time pequeno, empresa);
- quem visita o site e o que cada tipo de visitante deve fazer;
- 3 a 6 sites de que ela gosta e 2 ou 3 de que não gosta, de qualquer área, com uma linha de motivo cada;
- o material real: textos, fotos, logo, números, clientes, links;
- o que já existe: domínio, site atual, e onde o site vai viver (código próprio, ou uma ferramenta como Wix, Webflow ou WordPress);
- a língua do site;
- o prazo, e se há sócio que também decide e como ele entra nas aprovações.

Grave as respostas em `insumos/respostas.md`. Devolva em uma tela o que você entendeu e o que ainda falta. Pare aqui.

## Parte 1. Pesquisa curta
- Veja os sites que ela mandou e mais 8 a 12 da categoria dela: metade dos líderes do setor, metade de projetos comuns do tamanho dela. Diga como escolheu. Se você depende de capturas, proponha a lista e reduza pra 6.
- Pra cada um, preencha a mesma ficha: o que a primeira tela diz, fundo claro ou escuro, tipo de letra, cor de destaque e pra que ela serve, imagem real ou ilustrada, que prova aparece e onde, e qual é a ação principal.
- Conte o que se repete. Separe o que é costume da categoria do que só os líderes fazem.
- Grave em `processo/pesquisa.md` e entregue: o que você viu, com a contagem; onde o gosto dela bate e onde briga com isso; e os limites (quantos sites, o que não abriu).

Pare aqui.

## Parte 2. Entrevista de gosto
Em rodadas de até 5 perguntas. Toda pergunta traz opções reais e numeradas, apresentadas do mesmo jeito (mesmo tamanho, mesmo recorte, legenda sem elogio). No fim de cada rodada, atualize `processo/perfil.md` e mostre só o que mudou.

**Rodada 1, o toque dela**
- Ranking de 6 a 8 páginas iniciais de fora da categoria: as 3 melhores, as 3 piores, uma linha de motivo.
- 6 a 8 pares "isto ou aquilo", cada lado com um exemplo: claro ou escuro, título direto ou visionário, pouco ou muito texto, quente ou frio, "eu" ou "nós". E quais 4 mais importam.
- De uma lista embaralhada de 30 palavras, com palavras negativas no meio: 5 que são o site e 5 que ele nunca pode ser.

**Rodada 2, este site**
- Confirme quem visita e o que cada um deve fazer, agora em ordem de importância.
- 4 escalas de 1 a 5, com um site de exemplo em cada ponta: amigo ou autoridade, jovem ou clássico, leve ou sério, pra todos ou pra poucos. Peça 1 ou 2 eixos fortes, porque tudo no meio não decide nada.
- A frase principal escrita em 4 tons: factual, visionário, técnico e institucional.
- Dos sites da pesquisa: 2 com que ela nunca quer ser confundida e 2 mais próximos do que ela quer.
- De cada site de que ela gosta: o que levar, o que não levar, e a que distância ficar dele.

**Rodada 3, três direções**
- Sem layout ainda. Cada direção traz o logo como está (ou o nome escrito), 5 cores com o código e o que cada uma significa, título, texto, botão, link e uma foto dela com o tratamento proposto, tudo com o conteúdo real. Monte as três numa página só, em `processo/direcoes.html`, pra ela abrir no navegador.
- Ela pode combinar ("a 2 com a cor da 1").
- Confira cada direção contra as palavras do sim e do nunca.

Pergunta sem resposta vira proposta marcada [a confirmar], nunca decisão calada. Feche com o perfil em uma tela. **Só siga com o ok dela.**

## Parte 3. Direção
Escreva o `DESIGN.md`, curto, com valores e não com prosa:
- **Logo:** arquivos, versões, tamanho mínimo, o que nunca fazer.
- **Cor:** neutros e destaque com código, o que cada cor significa, e os pares de texto e fundo com o contraste calculado e mostrado (4,5 pra 1 no texto; 3 pra 1 em texto grande, borda e ícone).
- **Tipo:** famílias com o papel de cada uma, tamanhos e pesos. Só fonte gratuita pra web, ou avise do custo antes.
- **Imagem:** o que é real, como se trata, o que é proibido.
- **Movimento:** o único momento da página e a duração dele.
- **Voz:** as palavras do sim e do nunca, e frases dela que servem de régua.
- **Componentes:** só os que a página inicial usa.

Pare aqui.

## Parte 4. Protótipo da página inicial, e a comparação antes de mostrar
Construa em `site/`:
- Com o conteúdo real. De onde veio cada número e cada frase fica em `processo/origens.md`, fora da página.
- A primeira tela diz o que é e pra quem, com frase direta, sem metáfora. Se o título for mais ambicioso, o subtítulo carrega a categoria.
- Prova espalhada pela página e de tipos diferentes, em vez de empilhada na primeira tela.
- Um momento de movimento, que explica algo, com até meio segundo. A página fica completa e legível sem script, e respeita quem pede menos movimento.
- Sem carrossel automático, sem sequestro de rolagem, sem nada girando sozinho.
- No celular (390 px de largura), nada de rolagem lateral, e o principal aparece na primeira tela.
- Leve: imagens otimizadas, e o conteúdo principal carregado em até 2,5 segundos.
- Acessível: foco visível, texto alternativo de verdade, HTML semântico.
- Fuja da cara de template: degradê roxo, cartões idênticos com ícone em cima, etiqueta em cima de todo título, número gigante com rótulo pequeno, tudo centralizado. Qualquer um deles pode aparecer com motivo. O sinal ruim é a combinação sem motivo.

Depois compare, antes de mostrar como pronto:
- Ponha o protótipo ao lado dos sites de que ela gosta e responda: está no nível deles em acabamento, hierarquia, respiro, imagem e letra? Faça até 3 passadas e mostre o que mudou em cada uma. Cumprir a lista acima não prova qualidade.
- Se você não vê a página pronta, peça uma captura no computador e uma no celular antes de comparar.
- Tempo de carregamento e largura no celular: meça, ou diga "não medi" e explique como ela mede.
- Diga como abrir a página no navegador dela.

Pare aqui.

## Parte 5. Teste de 5 segundos
- Antes de qualquer leitor, preencha `processo/gabarito-teste.md`. O gabarito não muda depois que as respostas chegam.
- Se você puder abrir agentes novos e sem contexto, use 3, um por tipo de visitante, vendo só a imagem da primeira tela. Nunca responda no lugar dos leitores.
- Se não puder, dê as 4 perguntas a ela. Ela mostra a página por 5 segundos a 3 a 5 pessoas e traz as respostas, e você confere contra o gabarito citando cada resposta como veio.
- Passa se: (a) e (b) certos em pelo menos dois terços dos leitores, (c) na ação pretendida em pelo menos dois terços, e (d) fora das palavras do nunca em todos.
- Conserte só o que falhou com 2 ou mais leitores. No máximo 2 rodadas. O que sobrar vira decisão dela, com a sua recomendação.
- Teste só com agentes levanta hipótese. Diga isso no resultado e recomende mostrar a pessoas.

## Entrega
O protótipo, o `DESIGN.md`, a comparação com os sites de que ela gosta, o placar do teste com as respostas dos leitores como vieram, a lista do que ficou em aberto de propósito, e o que falta pra publicar.

## O que você não faz sem o ok dela
Publicar, fazer push, mexer no site que já existe, comprar domínio, criar conta, gastar dinheiro ou enviar qualquer coisa em nome dela.
