# Ideias pendentes

Esta lista contém apenas propostas ainda não implementadas. Ao concluir uma ideia, remova-a desta lista e registre o resultado na documentação da atualização correspondente.

## Mundos temáticos com 20 biomas cada

**Status:** ideia registrada e refinada a pedido do usuário em 17/10/2026. Este pedido autoriza somente documentar a proposta; os mundos e as artes ainda não foram implementados. Os temas foram solicitados pelo usuário; organização, exemplos de cenários e progressão abaixo são sugestões para desenvolver a ideia.

### Estrutura principal

Transformar a aventura em uma coleção de mundos com identidade própria. Os 20 biomas existentes formam o **Mundo Clássico**, preservando cenários, mobs e progresso. Cada mundo adicional também terá **exatamente 20 biomas**; mundo é a aventura temática completa, e bioma é uma região dentro dela.

Cada mundo deve ter uma capa marcante, um mapa com seus 20 biomas, cenários próprios, elenco de mobs e chefes coerentes e recompensas visuais reconhecíveis. Evitar apenas trocar a cor dos mesmos inimigos. Manter o combate e os controles familiares; a variedade vem dos ambientes, criaturas, encontros e apresentação de cada tema.

Conforme a nova ideia registrada em 17/10/2026, o **Universo dos Youtubers será o último mundo** e a chegada a ele liberará uma superárvore permanente. A ordem dos mundos intermediários ainda será definida. Ver [Superárvore final](#superárvore-final-no-mundo-dos-youtubers).

### Mundos propostos

| Mundo | Identidade | Exemplos de regiões dentro dos 20 biomas |
| --- | --- | --- |
| Clássico | A aventura atual de Minecraft | Os 20 biomas que já existem, preservados |
| Era dos Dinossauros | Natureza pré-histórica em estilo voxel; criaturas pequenas até grandes predadores | Planície jurássica, floresta de samambaias gigantes, pântano dos espinossauros, penhascos dos pterossauros e cratera vulcânica |
| Universo dos Brinquedos | Referência Toy Story/mods de brinquedos; personagem em escala pequena, objetos cotidianos gigantes | Quarto de brinquedos, castelo de blocos, circuito de carrinhos, quintal e depósito de brinquedos |
| Universo dos Mods | Criaturas e ambientes de mods de Minecraft escolhidos para o projeto | Selecionar os mods e suas referências antes de definir as 20 regiões, mobs e direção artística |
| Universo dos Youtubers | Regiões inspiradas nos criadores escolhidos e em suas identidades visuais; Edukof já indicado pelo usuário | Incluir a referência “Escadona” do Edukof, além de propostas como estúdio em blocos, cidade da comunidade e cenário de série; demais criadores e regiões ainda a definir |

**Referência confirmada pelo usuário em 17/10/2026:** “Escadona” é relacionada ao youtuber **Edukof** e pertence à proposta do Universo dos Youtubers. Não tratá-la como um mod desconhecido ou um mundo separado por suposição. As referências visuais específicas, mobs e composição da região ainda precisam ser reunidos antes de produzir as artes.

Esses exemplos não substituem o catálogo: antes de produzir cada mundo, definir seus **20 biomas distintos**, mobs, chefes, paletas e referências. Dinossauros, brinquedos, mods e youtubers devem continuar parecendo parte do mesmo jogo, com acabamento voxel e a interface Minecraft já adotada.

### Progressão sugerida

- Organizar os 20 biomas em **quatro capítulos de cinco regiões**, com mudanças claras no ambiente e encontros importantes ao final dos capítulos. O bioma 20 encerra o mundo com um chefe temático.
- Desbloquear o próximo mundo por uma conquista permanente de conclusão do anterior. Proposta inicial: vencer seu chefe final; custos ou requisitos adicionais ficam para uma etapa de balanceamento, sem preços inventados agora.
- Permitir revisitar mundos e biomas já liberados, com progresso e melhor marca separados por mundo. Entrar ou voltar de mundo não deve apagar a aventura anterior nem disparar uma Ascensão.
- Preservar pets, Diamantes, Obsidiana, melhorias permanentes e compras existentes. Definir o comportamento de Poder e melhorias temporárias antes da implementação, respeitando as regras de Ascensão já aprovadas.
- Balancear a transição para que o primeiro bioma do mundo seguinte avance a progressão do anterior. Não voltar ao nível de dificuldade do bioma 1 clássico; evitar também saltos que tornem o novo conteúdo impraticável. O equilíbrio de clique, passivo e pets deve ser avaliado em conjunto.
- Usar as moedas, classes, árvore e menus existentes sempre que possível. Esta ideia não reintroduz extração, criação de itens ou os sistemas já retirados das classes.

### Navegação e apresentação

O menu **Mundo** passa a abrir uma galeria de capas dos mundos. Ao escolher uma capa, exibir seu mapa de 20 biomas, progresso e requisitos; ao selecionar um bioma, mostrar a prévia, mobs, melhor marca e a ação de viajar. Usar transições suaves e manter o acabamento de inventário/hotbar existente.

Mundos bloqueados mostram uma prévia bonita e o requisito de acesso. Os biomas de cada capítulo devem ter silhuetas, cores e cenários diferentes, para que o jogador reconheça onde está sem depender apenas de texto. Mostrar claramente o mundo e o bioma atuais na arena e nas telas de viagem.

### Imagens individuais e bonitas

- Uma capa exclusiva por mundo e **20 fundos exclusivos por mundo**, um para cada bioma. Criar cenas completas individualmente; não gerar uma imagem grande para recortar e reutilizar em vários lugares.
- Mobs, chefes e eventuais pets temáticos recebem artes próprias. Criaturas usadas na arena devem ter recorte transparente real e boa definição, separado do fundo do bioma.
- Preparar uma direção artística por mundo: paleta, iluminação, materiais, escala, referências e pontos de destaque. Variar os ambientes de verdade; evitar cenários genéricos e variantes quase iguais.
- Usar fundos e capas com masters de 3840×2160 quando produzidos, documentando a dimensão real da origem e qualquer ampliação. Criar versões leves para mapa, celular e prévias; não carregar todos os fundos em 4K ao abrir o jogo.
- Priorizar a imagem do destino antes de entrar na arena, para evitar fundo cinza na primeira entrada. Carregar os outros mundos e seus biomas sob demanda, preservando fluidez e qualidade.
- Manter referências e origem de cada arte registradas, com uma correspondência clara entre mundo, bioma e arquivo. Os temas Toy Story, mods e youtubers exigem referências concretas antes de criar as imagens.

### Preservação e preparação técnica

O código atual usa o conceito de `world` também para os biomas existentes. Antes de implementar, separar a identidade de mundo da identidade de bioma, mantendo compatibilidade com os IDs e saves atuais. Um save antigo deve abrir no mesmo ponto do Mundo Clássico, sem perder saldo, progresso, compras ou pets.

Não aumentar apenas a lista atual de 20 para 100 posições e confundir os dois conceitos. Reservar uma identidade estável para cada mundo e seus 20 biomas, e registrar o maior avanço por mundo. Rever preços dos projetos, herança, missões e rankings que hoje dependem do maior bioma, para evitar descontos ao viajar, progressão zerada ou valores descontrolados na passagem para outro mundo. Critérios finais serão definidos com o balanceamento.

### Próximos passos antes de implementar

1. Reunir referências visuais da “Escadona” do Edukof, definir os demais youtubers e selecionar os mods que terão conteúdo temático.
2. Escolher qual mundo adicional será produzido primeiro e fechar seu catálogo de 20 biomas, mobs e chefes.
3. Definir desbloqueios, curva de dificuldade e interação com Ascensão, projetos e ranking.
4. Produzir as imagens individuais e validar navegação e desempenho no computador e no celular.
5. Implementar e validar um mundo completo por vez, preservando os 20 biomas clássicos e os saves existentes. O catálogo final de cada mundo terá 20 biomas; não publicar mundos incompletos como se estivessem concluídos.

## Superárvore final no Mundo dos Youtubers

**Status:** ideia solicitada em 17/10/2026, registrada para o futuro, sem implementação. Depende da expansão dos mundos. Nome provisório sugerido: **Legado Supremo**. Quantidades, nomes de itens e efeitos abaixo são propostas de refinamento, não decisões já implementadas.

### Requisitos definidos pelo usuário

- Ser maior que **todas as outras árvores somadas**, e ainda exceder esse tamanho de forma perceptível.
- Liberar somente quando o jogador **chegar ao último mundo, o Mundo dos Youtubers**.
- Ser o principal fator de longevidade associado à meta de **100 horas de jogo**.
- Conter muitos itens únicos, referências a **mods e youtubers** e **vários projetos novos de Obsidiana**.

### Dimensão e identidade sugeridas

A comparação deve considerar tanto a **quantidade de habilidades** quanto a **área efetivamente ocupada pelo mapa**. Aumentar só o zoom, o espaço vazio ou o tamanho dos ícones não atende à ideia. Antes de produzir, somar todas as árvores comuns que existirão naquele momento e dimensionar a superárvore acima desse total.

Como referência de planejamento, o Legado dos Mobs atual reúne 94 habilidades. Uma proposta inicial seria **cerca de 150 habilidades significativas**, com uma margem de pelo menos 50% sobre a soma das árvores comuns; recalcular essa meta se outras árvores forem adicionadas antes. O número 150 é uma sugestão, não um limite nem autorização para criar conteúdo agora.

Criar um grande mapa de constelações ou ilhas conectadas: regiões dedicadas a mods, regiões dedicadas aos criadores escolhidos e um núcleo final que integra seus legados. Cada região deve ter silhueta, materiais, cores, projetos marcantes e uma imagem própria. A região do Edukof inclui a referência **Escadona**, já confirmada pelo usuário. Os demais criadores e mods ainda precisam ser escolhidos e ter referências reunidas.

Manter zoom, arrastar, busca por item/projeto e atalhos de enquadramento por região como proposta de navegação. A visão geral deve mostrar o tamanho da árvore; a aproximação deve permitir ler cada habilidade sem poluir a tela. Revelar caminhos gradualmente, com prévia dos grandes marcos e indicação clara do que falta para desbloquear cada um.

### Acesso e progressão

O primeiro núcleo fica acessível **na primeira chegada ao Mundo dos Youtubers**, sem exigir terminar seus 20 biomas. O desbloqueio é permanente: voltar a outro mundo ou ascender não bloqueia a superárvore novamente.

Sugestão: os caminhos iniciais acompanham os primeiros biomas do último mundo; os projetos intermediários acompanham seus capítulos; os grandes marcos finais envolvem seus últimos biomas e chefes. Não acrescentar exigência de concluir todas as árvores antigas para abrir o núcleo, pois o requisito solicitado é chegar ao último mundo.

Distribuir a evolução em compras frequentes, projetos intermediários e objetivos raros de grande impacto. Evitar longos trechos sem nada comprável e nós repetidos criados apenas para aumentar a contagem. Novas compras devem ter prévia do efeito real, custo legível e identidade própria.

### A meta de 100 horas

A superárvore será o principal objetivo de longo prazo após alcançar o conteúdo final. **100 horas é uma meta de experiência e progressão**, não uma promessa de duração exata nem um contador que obrigue o jogador a esperar 100 horas para começar a comprar.

Ao fechar o balanceamento, explicitar se a meta será medida na jornada completa ou no período de conclusão do conteúdo final; não transformar essa frase automaticamente em 100 horas adicionais ou em um bloqueio de tempo. A proposta é alcançar longevidade por decisões, conquistas, projetos e evolução real.

Rever em conjunto os custos e marcos de tempo das árvores comuns, da superárvore, dos mundos e da oferta de Obsidiana. A árvore atual já tem marcos de 100 horas e cenários de orçamento que ultrapassam essa duração; simplesmente acrescentar uma árvore gigante com preços altos não garante a meta desejada. Simular diferentes ritmos de clique, passivo, Ascensão e participação nas invasões, considerando acúmulo de moeda antes do desbloqueio e evitando que os jogadores antigos comprem tudo imediatamente.

### Itens únicos e novos projetos de Obsidiana

Proposta inicial: **12 a 18 projetos novos**, distribuídos pelas regiões, com imagens individuais, referências reconhecíveis e efeitos próprios. Os nomes abaixo são provisórios; o catálogo final depende dos mods e criadores escolhidos.

| Exemplo de item/projeto | Direção de efeito a explorar |
| --- | --- |
| Escadaria do Legado — referência Escadona/Edukof | Evolução em patamares por conquistas permanentes do último mundo, com mudanças visuais nos grandes marcos; não criar construção ou extração |
| Reator Supremo — região de mods tecnológicos | Pulsos de dano passivo calculados a partir da produção real, com frequência e ganho limitados e claramente apresentados |
| Prisma do Impacto — região de mods mágicos | Dar utilidade a parte da chance crítica que ultrapassaria o limite, convertendo-a em impacto limitado sem alterar o teto de probabilidade |
| Elo dos Companheiros — região de criaturas de mods | Sinergias entre pets efetivamente equipados; não contar pets guardados nem conceder vantagens por duplicatas infinitas |
| Eco do Criador — região de youtubers | Evolução do poder ativo da classe com um eco temático e efeito legível, respeitando a identidade fixa da classe |
| Núcleo da Convergência — marco final | Combinar as conquistas das regiões em um benefício final relevante e uma conclusão visual especial |

Esses exemplos são pontos de partida para efeitos distintos, não uma lista fechada de projetos. Completar o restante do catálogo com referências reais dos mods e youtubers escolhidos, verificando o que já existe no Legado dos Mobs para evitar renomear os mesmos bônus.

Os projetos continuam usando **Obsidiana para desbloqueio permanente**. Podem liberar novas melhorias na Bigorna, seguindo o sistema existente, com custos e persistência explicitados antes de comprar. Não introduzir moeda premium, pagamentos, extração ou criação de itens. Não reutilizar os seis projetos atuais como se fossem novos, nem alterar retroativamente compras existentes.

Priorizar efeitos que mudem a forma de evoluir, com fatores próprios e limites claros, em vez de uma sequência de aumentos percentuais quase imperceptíveis. Clique, passivo, críticos, pets e poderes ativos devem ter opções úteis. Aplicação em Warden, invasão normal, temporada semanal e jogo offline precisa de regra e validação próprias; nenhum efeito desta proposta autoriza mudar suas contribuições ou recompensas atuais.

### Arte, preservação e preparação

- Usar artes individuais bonitas para itens e projetos, respeitando o padrão de qualidade dos novos mundos e as referências selecionadas. Criar capas e grandes composições por região; evitar uma imagem única recortada para todos os ícones.
- Mostrar a evolução visual do mapa à medida que regiões são concluídas. Efeitos de conclusão devem respeitar redução de movimento e manter o jogo fluido.
- Preservar IDs, compras e bônus das árvores atuais, pets, carteiras e progresso. O desbloqueio e as compras da superárvore devem sobreviver a Ascensão e viagem.
- Preparar a navegação e renderização para centenas de nós sem recalcular toda a árvore em cada clique. Carregar artes de detalhes sob demanda e evitar animações contínuas em todos os nós.
- Antes de implementar: fechar catálogo de referências, tamanho total, efeitos e limites, projetos, curva de custos e critério das 100 horas; então validar preservação de saves e balanceamento em cenários representativos.

## Baús e pets temáticos por mundo

**Status:** ideia solicitada em 17/10/2026, registrada sem implementação. O usuário delegou o planejamento do balanceamento dos desbloqueios, incluindo intervalos diferentes entre biomas. O calendário abaixo é a distribuição definida para a proposta, ainda sujeita à validação do jogo quando os mundos forem implementados.

### Conteúdo e identidade

Adicionar **sete baús novos em cada mundo adicional**, com catálogo de pets próprio e relacionado ao tema. Preservar os baús e pets atuais do Mundo Clássico. Uma meta inicial de seis pets por baú representa 42 pets por novo mundo; o catálogo e as raridades serão fechados antes da produção das artes, sem preencher slots com cópias apenas para atingir a quantidade.

- **Dinossauros:** pets de espécies pré-históricas e baús com materiais e ambientes do mundo, distinguindo criaturas terrestres, aquáticas e voadoras.
- **Brinquedos:** personagens e criaturas de brinquedo, peças de blocos, robôs e figuras ligadas às referências escolhidas, com identidade visual própria.
- **Mods:** criaturas reconhecíveis dos mods selecionados; cada baú deve refletir sua região e não misturar referências sem relação com ela.
- **Youtubers:** pets dos criadores escolhidos e de referências de seus conteúdos. Incluir Edukof/Escadona na composição temática. O usuário permite **fotos reais dos youtubers**, sem obrigar transformar todos em personagens voxel.

### Calendário de desbloqueio

O número identifica o **bioma dentro daquele mundo**, não um índice compartilhado com os outros. O primeiro baú fica disponível na chegada; os seguintes alternam objetivos mais longos e pequenas sequências de recompensa. O sétimo é o baú de encerramento, acessível ao chegar ao bioma 20, sem exigir vencer seu chefe para começar a obter pets que ajudem nessa luta.

| Mundo adicional | Baú 1 | Baú 2 | Baú 3 | Baú 4 | Baú 5 | Baú 6 | Baú 7 |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Dinossauros | 1 | 5 | 6 | 10 | 14 | 18 | 20 |
| Brinquedos | 1 | 3 | 7 | 8 | 13 | 17 | 20 |
| Mods | 1 | 4 | 5 | 9 | 14 | 18 | 20 |
| Youtubers — último mundo | 1 | 5 | 6 | 11 | 15 | 18 | 20 |

Exemplo: em Dinossauros, depois do baú do bioma 1 são quatro biomas até o próximo; do baú 2 para o 3, apenas um. Em Brinquedos, a sequência curta acontece entre 7 e 8; em Mods, entre 4 e 5. Assim, a chegada de novos baús não fica sempre no mesmo ritmo em todos os mundos. Entre os marcos, o jogador continua avançando biomas, evoluindo pets e comprando melhorias existentes; não acrescentar bloqueios por relógio para prolongar a espera.

O desbloqueio é uma conquista permanente baseada no maior bioma **alcançado naquele mundo**. Visitar outro mundo ou ascender não bloqueia novamente um baú já liberado. A galeria deve mostrar o próximo baú, o bioma necessário e quantos biomas faltam, com capa e silhuetas do catálogo.

### Equilíbrio dos pets e das compras

- Cada novo baú deve trazer uma evolução útil, sem tornar todos os pets anteriores inúteis imediatamente. Um raro forte do baú anterior pode continuar equipado enquanto o jogador procura algo melhor no novo.
- O ganho entre baús deve acompanhar a distância real entre seus biomas. Um desbloqueio após apenas um bioma terá um avanço de poder menor do que outro após quatro ou cinco; não aplicar o mesmo salto de multiplicador a todos.
- Como curva inicial de projeto, usar um fator de referência de **1,12 por bioma de diferença** para a base dos novos pets: um bioma corresponde a cerca de +12%, quatro a +57% e cinco a +76%. Esses valores são relações entre bases equivalentes, não multiplicadores finais já aplicados ao jogo. Ajustar pela progressão dos mobs na validação.
- Comparar raridades mantendo nível e evolução iguais: raridade superior deve ter multiplicador superior, sem empates acidentais. Treino e versões especiais continuam podendo fazer um pet antigo superar um novo; “Equipar melhores” deve usar o multiplicador efetivo atual.
- A base do primeiro baú de um novo mundo deve considerar a equipe normalmente obtida no anterior, para oferecer evolução sem zerar o valor dos pets raros antigos. Não reiniciar a escala de força no primeiro bioma de cada mundo.
- Definir preços fixos por baú a partir de um personagem de referência e da renda esperada na região; não cobrar com base no saldo ou na força ao vivo de cada jogador. Baús vizinhos precisam de diferenças de preço coerentes com seu ganho, e a progressão não deve depender de conseguir a maior raridade para atravessar um bioma obrigatório.
- Preservar as regras já aprovadas de abertura simples, lote de cinco, venda automática, cálculo de sorte e evolução. Não alterar chances dos baús atuais ou o preço dos lotes apenas por registrar esta ideia. Na implementação, exibir as chances reais após os bônus e evitar que a venda automática de um mundo seja aplicada por engano em outro.

### Fotos e artes únicas

Cada baú e cada pet terão **imagem própria**, criada ou selecionada individualmente. Não reutilizar a mesma foto ou ilustração para pets diferentes, nem recortar uma imagem coletiva para fingir várias artes. Capas de baú, imagens da abertura e pets devem continuar seguindo os formatos próprios dessas telas.

Para youtubers, selecionar uma foto real de boa qualidade do criador correspondente, registrar sua origem e preparar um recorte/composição que fique legível no slot, na roleta e no ranking. Não buscar fotos agora: os criadores e imagens serão definidos quando a ideia for executada. Se houver variantes visuais do mesmo criador, usar imagens/composições distintas e claramente identificáveis; evitar reaproveitar a mesma foto apenas com uma cor por cima.

Para os demais mundos, produzir ilustrações individuais com silhuetas e materiais diferentes, incluindo transparência real onde a interface usa recortes. Exportar versões leves para listas e miniaturas; manter qualidade sem carregar todas as imagens grandes de todos os mundos ao entrar no jogo.

### Preservação e validação futura

Usar IDs estáveis que identifiquem mundo, baú e pet, sem substituir os IDs do catálogo clássico. Preservar inventário, equipe, níveis, evoluções, pets exclusivos e restrições de proprietário atuais. Fotos reais de youtubers não mudam essas regras de exclusividade dos pets já existentes.

Antes de implementar, montar o catálogo completo de cada mundo e simular os sete desbloqueios com equipes comuns e raras, renda de clique/passivo, custos, treino e bônus da superárvore. Verificar abertura e débito únicos, sorte real, lotes, venda automática e consistência das imagens entre vitrine, roleta, inventário e ranking. O pedido atual atualiza somente a ideia e seu planejamento de desbloqueio.

## Requisito dinâmico do bônus de Poder na Ascensão

**Status:** ideia solicitada em 17/10/2026, registrada sem implementação. O usuário quer aumentar o Poder necessário para obter o bônus máximo quando a árvore já estiver avançada, calculando primeiro o grau desse avanço. A proposta altera o **requisito para atingir o máximo**, mantendo inicialmente o máximo de **25 Obsidianas da parcela de Poder**. Não confundir esse limite com a recompensa total da Ascensão.

### Situação atual verificada no código

Em `js/event-balance.js`, a parcela de Poder é `min(25, floor((Poder / 1.000.000)^0,35))`. Ela alcança 25 a partir de aproximadamente **9.865.391.181 de Poder**; portanto, com 10 bilhões já está no máximo, como relatado pelo usuário.

O cálculo usa o saldo disponível da jornada descontado o Poder inicial herdado (`getAscensionEarnedPower`), não todo o Poder produzido ao longo da conta. Combates, exploração, eventos e dedicação acrescentam até outras 15 Obsidianas: a base total pode chegar a 40 antes dos bônus da árvore. A recompensa efetivamente paga ainda respeita esses bônus e a reserva disponível. Nada disso foi alterado por este registro.

### Como medir uma árvore avançada

Usar **progresso ponderado de compras permanentes**, em vez de apenas quantidade de nós, saldo de Obsidiana, total de Ascensões ou tempo conectado.

1. Atribuir a cada habilidade registrada um peso de referência baseado no seu custo de projeto. Esse peso precisa ser versionado e estável; não é uma cobrança nem uma reconstrução do gasto histórico do jogador.
2. Somar os pesos das habilidades realmente adquiridas, contando cada ID válido uma vez e ignorando IDs desconhecidos.
3. Dividir pela soma dos pesos do catálogo de referência. O catálogo atual tem **94 habilidades**, com soma de custos de referência de **12.756**.
4. Considerar **30% de progresso ponderado** como início da escala avançada nesta proposta: pelo menos 3.827 pontos de referência adquiridos. Isso não significa necessariamente 30% da quantidade de nós.

Exemplo: uma habilidade com peso 100 contribui mais para o avanço que uma de peso 5, reduzindo o incentivo a comprar apenas muitos nós baratos. Descontos, saldo gasto em outras lojas, recompensas da invasão e a ordem das compras não modificam a medida. Compras antigas valem normalmente, sem exigir que o jogador pague novamente a diferença dos preços reajustados.

O cálculo não foi aplicado a uma conta específica; os percentuais abaixo são cenários de planejamento. O percentual real de cada jogador deve ser obtido de suas compras quando a ideia for implementada.

### Escala inicial calculada

Definir `p` como o progresso ponderado entre 0 e 1 e `T₀ = 1.000.000 × 25^(1/0,35)`. Proposta de escala contínua:

```text
S(p) = 10^max(0, (p − 0,30) / 0,10)
Poder para o bônus máximo = T₀ × S(p)
```

Até 30%, preservar o requisito atual. Acima disso, cada dez pontos percentuais de avanço multiplicam por dez o Poder necessário, com crescimento contínuo entre os marcos, sem saltos artificiais em faixas fechadas.

| Avanço ponderado | Peso adquirido mínimo aproximado | Poder necessário para as 25 Obsidianas |
| --- | ---: | ---: |
| Até 30% | Até o marco de 3.827 | Cerca de 9,865 bilhões |
| 40% | 5.103 | Cerca de 98,654 bilhões |
| 50% | 6.378 | Cerca de 986,539 bilhões |
| 60% | 7.654 | Cerca de 9,865 trilhões |
| 80% | 10.205 | Cerca de 986,539 trilhões |
| 100% | 12.756 | Cerca de 98,654 quadrilhões |

Os percentuais intermediários e preços discretos dos nós podem colocar uma conta ligeiramente acima desses marcos. Os valores da tabela são os alvos matemáticos nos percentuais exatos, não medições de contas reais. A intensidade de ×10 a cada dez pontos é uma **proposta de balanceamento**, não um resultado já validado em combate; deve ser simulada com a produção e os bônus reais antes de aplicar.

Para manter a forma atual da curva, usar o fator `S` também no cálculo das parcelas intermediárias de Poder, com uma proteção para a recompensa inicial:

```text
Se o Poder válido da jornada for menor que 1.000.000: parcela de Poder = 0.
Caso contrário: parcela de Poder = min(25, max(1, floor((Poder / (1.000.000 × S))^0,35))).
```

Assim, a Ascensão continua liberando com o requisito mínimo existente e pelo menos uma unidade dessa parcela quando elegível; o alvo para chegar a 25 acompanha a árvore. Não aumentar automaticamente o prêmio máximo junto do requisito, pois isso pode anular a intenção de reduzir a facilidade de saturar a recompensa.

### Clareza, estabilidade e preservação

- Mostrar na Ascensão o **avanço ponderado da árvore**, o requisito vigente para as 25 Obsidianas, o Poder válido da jornada e a próxima parcela. Explicar que 25 é o teto dessa fonte e separar bônus, outras fontes e limite da reserva.
- Proposta de estabilidade: registrar o progresso e o fator usados no início de cada jornada. Compras feitas durante ela atualizam o alvo da jornada seguinte, com aviso explícito, sem diminuir inesperadamente a prévia da Ascensão já em preparação. Para saves antigos sem esse registro, preservar a regra da jornada atual na migração e iniciar a escala na próxima.
- Não recalcular o progresso histórico a partir de saldo, não debitar moeda, não recuperar Obsidiana já recebida e não apagar compras. Ascensão e viagem não devem diminuir o marco permanente já reconhecido.
- Manter pesos e catálogo de referência versionados. Alterar preços da loja ou adicionar nós não deve fazer uma conta parecer menos avançada ou baratear seu alvo automaticamente. A superárvore final precisará acrescentar uma etapa de escala própria, preservando os marcos anteriores; não aumentar apenas o denominador e diluir o progresso de quem completou as árvores comuns.
- Preservar a exclusão do Poder herdado, o mínimo para Ascensão, as outras quatro fontes, os multiplicadores existentes e a reserva. A fórmula e a interface devem usar a mesma regra, incluindo a inversão para mostrar o requisito da próxima Obsidiana.
- Antes de implementar, simular personagens de clique e passivo em vários biomas, com árvores concentradas em ramos diferentes, reserva cheia/vazia e diferentes ofertas de Obsidiana. Validar o efeito sobre os projetos e a meta de 100 horas; não compensar uma curva excessiva adicionando esperas obrigatórias.
- Verificar limites numéricos, arredondamento imediatamente antes/depois de cada recompensa, salvamento, migração, viagens, Ascensão e expansão para os novos mundos. Nenhum número desta proposta autoriza alterar a economia ao vivo agora.
