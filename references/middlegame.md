# Referência: Meio de Jogo

## Sumário

1. [Avaliação de posição](#avaliacao)
2. [Estruturas de peões](#estruturas)
3. [Os elementos posicionais clássicos](#elementos)
4. [Planejamento](#planejamento)
5. [Motivos táticos](#taticos)
6. [Ataques](#ataques)
7. [Trocas: quando e por quê](#trocas)
8. [Profilaxia](#profilaxia)

---

## <a name="avaliacao"></a>1. Avaliação de posição

Antes de fazer um plano, é preciso avaliar honestamente a posição. Use o
**checklist clássico de Steinitz**, refinado posteriormente:

### Fatores estáticos (não mudam fácil)
1. **Material**: vantagem material? Equilíbrio? Compensação?
2. **Estrutura de peões**: peões fracos (isolados, dobrados, atrasados)?
   Peões passados? Maioria móvel?
3. **Casas fracas e fortes**: casas que não podem ser defendidas por peão
   se tornam "buracos" — ótimos postos avançados (outposts)
4. **Posição dos reis**: castelados? Castelos sãos? Onde está o ataque?

### Fatores dinâmicos (podem mudar rápido)
5. **Atividade das peças**: peças bem colocadas vs. peças passivas
6. **Coordenação**: peças trabalhando juntas?
7. **Iniciativa**: quem dita o ritmo? Quem está fazendo ameaças?
8. **Tempo**: quem tem tempo para se preparar?

### Pergunta-chave (de Mark Dvoretsky)
> "Qual é a minha pior peça? Como melhoro?"

A regra prática: **um plano sempre começa por melhorar a peça com menos
mobilidade**.

---

## <a name="estruturas"></a>2. Estruturas de peões

A "esqueleto" da posição. Define onde estão as casas fracas, onde abrir
arquivos, e em que lado atacar.

### Peão Dama Isolado (IQP — Isolated Queen Pawn)
- Peão branco em d4 (ou preto em d5) sem peão de defesa na coluna c ou e
- **Pontos fortes para quem tem IQP**:
  - Casa de outpost em e5/d5 (ou e4/d5)
  - Espaço, atividade de peças, ataques no flanco do rei
- **Pontos fortes para quem joga contra**:
  - O peão é alvo permanente; final é favorável a quem joga contra
  - Bloqueio em d5 (ou d4) com cavalo
- **Plano para quem tem IQP**: usar peças, atacar; evitar trocas de peças
- **Plano contra**: trocar peças, ir para o final
- **Aparece em**: Tarrasch, QGA, Caro-Kann Panov, Petroff

### Peões pendurados (Hanging Pawns)
- Peões em c5 e d5 (ou c4 e d4), sem peões adjacentes
- Forte enquanto avançam ou ameaçam; fraco quando bloqueado
- **Aparece em**: Tartakower QGD, alguns Sicilianos

### Estrutura Carlsbad
- Brancas têm peões a2/b2/c3/d4 + e3/f2/g2/h2
- Pretas têm a7/b7/c6 + d5/e6/f7/g7/h7
- **Plano branco**: **ataque de minoria** — avançar a-pawn e b-pawn (a4, b4, b5)
  para criar um peão atrasado em c6 (ou c7) das pretas
- **Plano preto**: atacar no flanco do rei com ...f5, ...e5
- **Aparece em**: QGD Trocada, alguns Slav

### Pirâmide francesa
- Peão preto em e6 com d5 e geralmente c6/f7
- Bispo de c8 (dama-bispo) é frequentemente ruim
- **Plano branco**: ganhar espaço com e5, atacar no flanco do rei
- **Plano preto**: contra-ataque em c5/f6; sair com o bispo c8 via b7 ou h6

### Estrutura Maroczy Bind
- Brancas: peões em c4 e e4
- Pretas: tipicamente em e6 e d6 (alguns Sicilianos acelerados, Defesa Inglesa)
- Branca ganha espaço; preta busca quebrar com ...b5 ou ...f5

### Estrutura Hedgehog (Ouriço)
- Pretas: peões em a6/b6/d6/e6 (linha "pelos" baixa, peças atrás)
- Forte porque é difícil atacar; preta espera momento de explodir com ...b5, ...d5
- **Aparece em**: certas variantes Sicilianas modernas, Inglesa

### Estrutura Stonewall
- Peões em c3, d4, e3, f4 (ou simétrico em preto: c6, d5, e6, f5)
- Forte em e5/e4 como outpost; bispo de casas claras é problema
- **Aparece em**: Holandesa Stonewall, Coronata, Bird

### Estrutura King's Indian
- Brancas: c4, d5, e4 (centro fechado)
- Pretas: d6, e5 com peões de flanco do rei avançando
- Jogo **assimétrico em alas opostas**: branca ataca rainha, preta ataca rei
- Velocidade da corrida define o jogo

### Cadeia de peões francesa (Centro Bloqueado)
- Brancas: d4, e5
- Pretas: d5, e6
- **Princípio de Nimzowitsch**: atacar a base da cadeia
  - Brancas atacam a base d5 com c4 e f5
  - Pretas atacam a base d4 com ...c5 e ...f6

---

## <a name="elementos"></a>3. Elementos posicionais clássicos

Os "imbalances" de Silman, refinados de Steinitz:

### Casas fracas / Outposts
- **Casa fraca**: casa que não pode mais ser defendida por peão
- **Outpost**: casa fraca avançada onde uma peça (geralmente cavalo) pode
  ficar sem ser expulsa por peão
- Cavalo em outpost na 5ª/6ª fila é uma das maiores forças posicionais
- **Exemplo clássico**: cavalo branco em e5 (ou d6) apoiado por peão em f4

### Bispo bom vs. bispo ruim
- **Bispo bom**: peões do próprio lado em casas de cor OPOSTA ao bispo
- **Bispo ruim**: peões na mesma cor do bispo (bloqueiam seu movimento)
- Exemplo: na Francesa, bispo preto de c8 é frequentemente ruim (peões em
  casas claras: e6, d5, etc.)
- **Decisão estratégica**: trocar o bispo ruim por uma peça ativa do
  adversário é geralmente bom

### Par de bispos
- Vale ~0.5 peão em posições abertas
- Vale mais quando o jogo se abre (final)
- Em posições fechadas, par de cavalos pode ser igual ou melhor

### Coluna aberta / semi-aberta
- **Coluna aberta**: sem peões de nenhum lado — domínio para torres
- **Coluna semi-aberta**: peão só de um lado — quem não tem peão pressiona o peão adversário
- Torre na 7ª/2ª fila ("torres no paraíso") é frequentemente decisiva
- Dobrar torres na coluna aberta multiplica força

### Peão passado
- Peão sem peão adversário na sua coluna ou colunas adjacentes
- Cresce em valor à medida que o jogo simplifica
- **Regra de Nimzowitsch**: "O peão passado deve ser bloqueado, depois neutralizado"
- Bloqueador ideal: o cavalo (porque ainda ataca outras coisas dali)

### Espaço
- Quem tem mais espaço pode manobrar peças com mais facilidade
- Princípio: **trocas favorecem o lado com menos espaço**

### Iniciativa
- Capacidade de ditar o ritmo, fazer ameaças, forçar respostas
- Iniciativa pode ser temporária — usar antes que evapore

---

## <a name="planejamento"></a>4. Planejamento

### Os 5 passos do planejamento posicional

1. **Avaliar a posição** (checklist acima)
2. **Identificar o desbalanço (imbalance) principal**: bispo vs cavalo,
   estrutura de peões, espaço, iniciativa
3. **Definir o objetivo**: criar fraqueza? Atacar rei? Promover peão?
4. **Encontrar candidatos de lance** que servem o objetivo
5. **Calcular** as linhas táticas para garantir que o plano funciona

### Tipos de planos comuns

| Plano | Quando aplicar | Como executar |
|---|---|---|
| **Ataque de minoria** | Estrutura Carlsbad | a4-b4-b5 criando peão atrasado |
| **Avanço da maioria** | Maioria de peões em uma ala | Avançar criando peão passado |
| **Aprofundar bispo** | Cavalo bom em outpost | Plantar cavalo em e5/d6 |
| **Dobrar torres** | Coluna aberta | Ra1-d1, Re1-d1 |
| **Penetração na 7ª** | Final com torres ativas | Forçar Rd1-d7 |
| **Ataque ao rei** | Material/peças concentrados na ala | Sacrifícios + abertura de linhas |
| **Aprofundar cavalo** | Posição fechada | Manobra Nf3-d2-c4 ou similar |
| **Troca de peças fracas** | Sua peça pior é melhor que a peça adversária | Forçar troca |

### Heurísticas de Capablanca
- "Estude finais primeiro — eles ensinam você a usar peças"
- "Um plano simples vale mais que vinte lances brilhantes mal coordenados"
- "Vitória vem do erro do adversário; provoque erros"

### Heurística de Lasker
- "A maior ameaça em xadrez é frequentemente uma ameaça posicional, não tática"

### Heurísticas de Steinitz
- "Defenda quando você está pior, ataque quando você está melhor"
- "O direito de atacar pertence a quem tem vantagem"

---

## <a name="taticos"></a>5. Motivos táticos essenciais

A tática é o que decide a maioria das partidas (mesmo em alto nível,
~70% das vitórias têm um erro tático decisivo). Memorize estes padrões:

### Padrões de captura

| Motivo | Definição |
|---|---|
| **Pino** | Peça presa porque atrás dela está uma peça mais valiosa |
| **Garfo** | Uma peça ataca duas (cavalo é o garfo-rei) |
| **Espeto** | Como pino, mas a peça mais valiosa está na frente |
| **Ataque descoberto** | Mover peça revela ataque de outra |
| **Cheque descoberto** | Variante mais forte do ataque descoberto |
| **Cheque duplo** | Duas peças dão cheque simultaneamente — só rei pode se mover |
| **Desvio** | Forçar peça defensora a abandonar seu posto |
| **Atração** | Atrair peça (rei) para casa fatal |
| **Sobrecarga** | Peça com duas defesas; tira uma e o resto cai |
| **Quebra-defesa** | Sacrifício para abrir linha contra rei |
| **Casa magnética** | Casa onde o rei é atraído (mate da retaguarda) |

### Padrões de mate

| Mate | Posição típica |
|---|---|
| **Mate do corredor** (back-rank) | Torre/dama na 8ª linha, rei sem fuga atrás de peões |
| **Mate de Anastasia** | Cavalo + torre, rei na borda |
| **Mate do beijo da morte** | Dama suportada beija o rei na borda |
| **Mate de Boden** | Dois bispos atacando rei castelado |
| **Mate árabe** | Cavalo + torre, rei no canto |
| **Mate de Lolli** | Sacrifício em f7 abrindo o rei |
| **Mate da Manjedoura** (smothered) | Cavalo + dama (sacrifício de dama) — clássico |
| **Mate de Damiano** | Sacrifício de torre seguido de dama |
| **Mate de Légal** | Sacrifício de dama com bispo+cavalo |

### Combinações famosas
- **Sacrifício de bispo em h7 (h2 para pretas)**: o "Sacrifício Grego",
  abre o rei castelado
- **Sacrifício de cavalo em f7**: padrão clássico em aberturas abertas
- **Sacrifício de torre em c3/c6**: típico em Sicilianas

---

## <a name="ataques"></a>6. Ataques

### Ataque no flanco do rei (com reis no mesmo lado)
Condições favoráveis:
1. Vantagem material ou de espaço na ala
2. Mais peças voltadas para o rei adversário
3. Estrutura de peões deslocada (h6 ou g6 jogados sem necessidade)
4. Possibilidade de abrir colunas (f4-f5, g4-g5)

Princípios:
- **Concentre peças** antes do ataque (4-5 peças voltadas para o rei)
- **Abra linhas** com peões ou sacrifícios
- **Não ataque com peças isoladas** — perdem força sozinhas

### Ataque com reis em lados opostos
- **Quem chega primeiro vence** — corrida pura
- Ambos avançam peões na frente do rei adversário
- **Não jogue peões na frente do próprio rei** (cria alvos)
- Sacrifício de material é frequentemente necessário para abrir linhas

### Defesa contra ataque
- **Trocar peças atacantes** — cada peça trocada enfraquece o ataque
- **Não criar fraquezas** com peões precipitados (não jogar h6/g6 sem motivo)
- **Contra-ataque no centro** — o melhor remédio contra ataque no flanco
- **Bloquear linhas** — bispo em h7 cobre coluna h, peça em g7 protege

---

## <a name="trocas"></a>7. Trocas: quando e por quê

### Quando trocar
- Você tem **menos espaço**: trocas aliviam aperto
- Você está **defendendo**: simplifica
- Adversário tem **par de bispos** e você só tem um: trocar bispo deles
- Você tem **bispo ruim**: troque pelo bispo ativo do adversário
- Você está a caminho do **final favorável**: simplificar
- Você tem **vantagem material**: cada troca aumenta a vantagem proporcional

### Quando NÃO trocar
- Você tem **iniciativa** ou ataque: trocas tiram pressão
- Você tem **mais espaço**: trocas favorecem adversário
- A peça que você trocaria é sua **única peça boa**
- A troca **abre a coluna errada** ou ativa peça inimiga
- A peça do adversário é **a única peça passiva dele**: não ative para ele

### Regra de Capablanca
> "Estude qual seria a posição APÓS a troca. Se você ficar pior, não troque."

---

## <a name="profilaxia"></a>8. Profilaxia

Conceito introduzido por **Nimzowitsch** em *My System*: pensar nos planos
do adversário e impedir antes de executar os seus.

### Pergunta profilática
> "Se fosse a vez do adversário, o que ele faria?"

Antes de jogar, considere o **lance ideal do adversário** e veja se você
pode impedir.

### Exemplos clássicos
- Jogar `a3` para impedir `...Bb4`
- Jogar `h3` para impedir `...Bg4`
- Jogar `Kh1` para tirar o rei do pino diagonal
- Jogar `Re1` antes de e5 para apoiar avanço

**Atenção**: profilaxia exagerada vira passividade. Não jogue `a3, h3,
Kh1` todos sem motivo concreto — perde tempos.

---

## Como usar esta referência durante análise

1. **No início do meio de jogo**, avalie a estrutura: qual é a do tipo?
2. **Identifique o plano correto** para essa estrutura (consulte tabelas acima)
3. **Aponte se o jogador seguiu** ou se desviou — e por quê
4. **Marque momentos de troca** problemáticos (trocou na hora errada)
5. **Identifique ataques** que foram bem ou mal conduzidos
6. **Aponte falhas profiláticas**: deixou o adversário executar plano sem
   incomodar?
