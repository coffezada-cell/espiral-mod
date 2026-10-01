# Espiral Arsenal

Mod para **Minecraft Java 1.20.1**, feito com **Fabric**. Confira as novidades de cada versão e baixe o JAR desejado.

| 📦 Versão atual | 📚 Histórico completo |
|:--|:--|
| [**Baixar Espiral Arsenal 0.3.1**](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.3.1/espiral-arsenal-fabric-0.3.1.jar) | [Ver todas as releases](https://github.com/coffezada-cell/espiral-mod/releases) |

## 📰 Atualizações

### 🆕 v0.3.1 · NPCs, exploração, alimentos e arsenal

#### Novidades do JAR atualizado

- **Agatha, Ivete e Sr. Veríssimo:** novos NPCs com skins, telas de diálogo e lojas próprias. Permanecem imóveis e não aparecem automaticamente no mundo; os ovos de invocação ficam na aba **Espiral: Itens de missão**.
- **Conversas e presentes:** a primeira conversa apresenta as mecânicas e entrega os presentes uma única vez por jogador. Depois dela, são liberadas as lojas e as falas casuais, incluindo as interações especiais com papagaio e cegueira.
- **Lojas da Ordem:** Agatha vende rituais, habilidades e itens paranormais; Ivete vende habilidades, armas e munições. Veríssimo oferece missões e mapas, renova suas ofertas a cada 20 minutos e troca relatórios e frascos elementais por créditos.
- **Modelos slim:** Agatha e Ivete agora usam braços slim, preservando suas skins. O modelo do Veríssimo permanece normal.
- **Animação de dano corrigida:** os três NPCs deixam de manter os braços e pernas animados indefinidamente após receber golpes. A reação ao dano termina normalmente, sem permitir que sejam empurrados ou saiam do lugar.
- **Baús elementais:** consomem a chave correspondente e podem ser usados novamente com outra chave. Sorteiam quatro recompensas de uma categoria, com chances iguais entre Armas, Rituais e Habilidades; os itens respeitam o elemento do baú, incluindo opções neutras. Durante os cinco segundos de abertura, exibem as recompensas girando, uma por vez, com partículas e sons de cada elemento. Os itens só ficam disponíveis para coleta ao fechar.
- **Estruturas:** adiciona oito estruturas elementais e a Ordo Realitas, com colocação manual e geração natural. O posicionamento usa a camada de grama como referência da superfície para preservar as partes subterrâneas.
- **Mapas elementais:** buscam estruturas do elemento correspondente e exibem suas marcações próprias. O destino é calculado ao abrir o mapa, a partir da posição atual do jogador, não ao comprá-lo. Os mapas das missões indicam o tipo de estrutura na descrição.

> A obtenção do Relatório de Missão ainda será definida; sua troca com Veríssimo já está disponível. A geração automática dos NPCs não foi ativada.

#### Alimentos, arsenal e melhorias anteriores

Adiciona oito alimentos, amplia o arsenal com o Punhal X e atualiza modelos, texturas e efeitos visuais.

- **Desértica** restaura 4 PE e causa náusea por 3 segundos. **Rubra** restaura 4 PE, causa náusea e saturação por 3 segundos, dá Força II e ativa Ódio Incontrolável por 40 segundos. Quando o ódio termina, começa a Dependência por 1 minuto; cada uso posterior da Rubra aumenta esse tempo em 30 segundos. **Vomitar Peste** redefine a dependência para 1 minuto.
- **Ganja** restaura 15 PE e causa náusea, fome II, fraqueza II e fadiga II por 7 segundos; tem 2 de durabilidade. **Maiser** restaura 4 PE, causa náusea por 4 segundos e 1 de dano. **Corotinho Sdol** restaura de 2 a 6 PE, causa náusea por 7 segundos e 2 de dano.
- **BomBoro** causa 1 de dano e sua recuperação de PE diminui a cada uso: começa em 4, pode chegar a valores negativos e volta a 4 quando o jogador dorme. Tem 4 de durabilidade. **Manteiga na Manteiga** restaura 20 de fome, 20 de saturação e 5 PE; após 5 minutos, remove 10 PE e causa fome II por 4 segundos. **Paçoca** restaura 1 pernil de fome, 10 de saturação e 8 PE.
- Adiciona a aba criativa **Espiral: Alimentos** e aplica as texturas próprias enviadas. Maiser, Desértica e Corotinho Sdol usam a animação de beber um frasco de água.
- **Correções ritualísticas:** Crânio consumido, Osso com lodo e Coração de Sangue recebem novos nomes. Dilacerar passa a atingir um único alvo, causar 6 de dano de Sangue e aplicar Sangramento por 6 segundos, sem curar o jogador.
- **Componentes de Conhecimento:** o Livro de São Cipriano mantém sua identidade e textura originais; o Tomo de Conhecimento é um item separado, com textura própria. Ambos servem para recarregar a bolsa de Conhecimento.
- **Maldições:** Lancinante converte o dano principal da arma em Sangue; Atemporal, em Morte; e Volátil, em Energia. Seus bônus e efeitos anteriores permanecem.
- **Amaldiçoar Arma:** os quatro rituais agora aceitam uma arma em qualquer mão. Com duas armas equipadas, apenas a da mão direita recebe o efeito.
- **Identidade visual:** adiciona o novo logotipo como ícone do mod na lista de mods do Minecraft.
- **Punhal X:** nova arma de categoria 2 com 6 de dano base, 10% de chance crítica e mais 2 de dano ao atacar agachado. Sua habilidade consome 4 PE e cria uma marca em uma área 3×3 no chão: o primeiro alvo que entrar recebe 20 de dano. A marca dura até 40 segundos, e é possível manter até três marcas ao mesmo tempo.
- **Rituais e partículas:** adiciona marcas X animadas e novos efeitos de raio de Energia. Armas 3D amaldiçoadas por rituais agora exibem um visual do elemento correspondente: Sangue, Morte, Energia ou Conhecimento.
- **Modelos e texturas:** atualiza as bancadas, Arcabuz, Punhal, Kemi, Sniper, Marreta e Escudoskate, incluindo sua aparência ao bloquear. Também renova ícones de efeitos, elementos da interface, miras, ladrilhos de barro e pinturas.
- **Correções visuais:** as armas afetadas por rituais exibem o padrão elemental sobre sua textura, como uma camada de encantamento, sem o preto e rosa. Os papéis de ritual de Conhecimento recuperam a textura original; a textura nova pertence ao Tomo de Conhecimento, componente que recarrega a bolsa do elemento.
- **Bancadas:** corrige laterais esticadas da Ritualística, o posicionamento visual dos objetos da Modificadora e a rotação das bancadas conforme a direção de colocação. O círculo da Ritualística também acompanha a orientação do bloco.
- **Kemi:** chance crítica base ajustada para 20%, inclusive na indicação do HUD.

[⬇️ Baixar v0.3.1](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.3.1/espiral-arsenal-fabric-0.3.1.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.3.1)

---

### v0.3.0 · Bolsas, componentes e círculo ritualístico

A atualização amplia a preparação de rituais e a decoração do mundo.

- **Bolsas elementais:** Sangue, Morte, Energia e Conhecimento têm 65 pontos de durabilidade e gastam 1 por conjuração. Com 1 ponto restante, a bolsa não quebra, mas não permite conjurar; combinar a bolsa com um componente do mesmo elemento recupera 3 pontos. Medo não usa bolsa nem componente.
- **Componentes e rituais:** adiciona componentes elementais e atualiza efeitos e descrições, incluindo Dilacerar. Revê Sombria, Lancinante e Vitalidade.
- **Bancada Ritualística:** forma um quadrado 3×3 com redstone ao redor da bancada para ativar o círculo. A redstone é consumida com partículas; sem o símbolo, ainda é possível consultar rituais, mas equipar ou remover exige a ativação.
- **Itens e construção:** adiciona receitas para munições, arcades e ladrilhos de barro com variantes de laje, escada e muro. O James Bones também aceita peixe cru ou assado.
- **Combate e interface:** o Machado Mutilador causa 16 de dano ao arremessar e precisa ser carregado. Separa as abas criativas e atualiza HUD, ícones e papéis de ritual.

[⬇️ Baixar v0.3.0](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.3.0/espiral-arsenal-fabric-0.3.0.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.3.0)

---

### v0.2.12 · Ajustes de HUD, bancadas e itens decorativos

- Adiciona quatro máquinas de fliperama, o bloco Tijolos de Lodo e três pinturas; atualiza modelos da Alabarda de Conhecimento, do Capacete do ???, da Lança e da Pistola da Dara.
- Atualiza ícones elementais e papéis de ritual. Os overlays dos capacetes ficam atrás da hotbar, sem reduzir o tamanho da textura.
- Corrige cálculo de dano no HUD e efeitos de armas e habilidades; revisa descrições de 39 itens e a exibição das pinturas na aba criativa.

[⬇️ Baixar v0.2.12](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.12/espiral-arsenal-fabric-0.2.12.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.12)

### v0.2.11 · Novas armas e integração com Better Combat

- Adiciona Antena, Ereshkigal, Leonora, Taco do Xande, Skate do Xande, Pistola da Dara, uma nova Sniper e Capacete do ???.
- Acrescenta compatibilidade opcional com Better Combat para combos e posturas de armas corpo a corpo.
- Aprimora a recarga individual de pistolas, revólveres e espingardas: trocar de arma cancela a recarga, e cada cartucho é inserido separadamente.

[⬇️ Baixar v0.2.11](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.11/espiral-arsenal-fabric-0.2.11.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.11)

### v0.2.10 · Armas de fogo e sistema de munição

- Adiciona Pistola, Revólver, Sniper, Rifle, Fuzil M4 e Espingarda, cada um com alcance, dano, cadência, carregador e munição correspondente.
- Introduz mira ao segurar o botão direito, zoom e retículo para a Sniper, disparo automático da M4 e recarga pela tecla **R**.
- Atualiza HUD e descrições para exibir munição e estado do carregador.

[⬇️ Baixar v0.2.10](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.10/espiral-arsenal-fabric-0.2.10.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.10)

### v0.2.9 · Manoplas e arsenal corpo a corpo

- Adiciona Bestial Contida e Bestial Descontrolada e ajusta Machado Mutilador, Ademar e outras armas.
- As Manoplas ocupam as duas mãos: ataques alternam entre esquerda e direita, enquanto a mão secundária fica protegida. A habilidade delas gasta PE e aumenta o dano por alguns segundos.
- Armas vanilla recebem categorias e podem receber o efeito de Amaldiçoar Arma; HUD passa a refletir bônus ativos.

[⬇️ Baixar v0.2.9](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.9/espiral-arsenal-fabric-0.2.9.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.9)

### v0.2.8 · HUD de combate e novos rituais

- Adiciona Velocidade Mortal, Guiado pelos Sussurros e Zona dos Sussurros, com efeitos e áreas próprios.
- O HUD passa a mostrar atributos da arma e ritual selecionado; reorganiza a barra de PE e incorpora bônus de chance crítica.
- Atualiza a Alabarda de Conhecimento, amplia áreas de rituais e organiza a biblioteca por páginas.

[⬇️ Baixar v0.2.8](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.8/espiral-arsenal-fabric-0.2.8.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.8)

### v0.2.7 · Biblioteca da Bancada Ritualística

- Reformula a bancada para aprender rituais por papéis e organizar os rituais conhecidos em uma biblioteca paginada.
- Permite preparar e remover rituais pela interface; duplicatas não são consumidas e espaços ativos continuam desbloqueados pela progressão.
- Migra para a biblioteca os rituais ativos de mundos existentes e corrige texturas dos machados.

[⬇️ Baixar v0.2.7](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.7/espiral-arsenal-fabric-0.2.7.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.7)

### v0.2.6 · Expansão para 23 rituais

- Adiciona 18 rituais, expandindo opções de Sangue, Morte, Energia e Conhecimento, como Purgatório, Dilacerar, Deflagração, Salto Fantasma e Teletransporte das Sombras.
- Implementa custos de PE, dano elemental, efeitos persistentes, partículas próprias, teletransportes e o efeito Paralisado dos Tentáculos de Lodo.
- Ajusta as regras de conjuração, incluindo o comportamento de Purgatório e Ódio Incontrolável.

[⬇️ Baixar v0.2.6](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.6/espiral-arsenal-fabric-0.2.6.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.6)

### v0.2.5 · Controles de rituais e combate revisado

- Consolida mudanças da etapa 0.2.4: seletor de rituais, conjuração pela tecla **V**, barra de PE e efeitos visuais por elemento.
- Armas de fogo passam a disparar pelo clique esquerdo, com recuo de câmera; Doze Alheia e Doze de Sangue podem alternar tiros enquanto o botão é segurado.
- Atualiza os modelos da Katana, do Colosso e das bancadas; bancada fica direcionada ao jogador ao ser colocada.

[⬇️ Baixar v0.2.5](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.5/espiral-arsenal-fabric-0.2.5.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.5)

### v0.2.3 · Progressão, elementos e modificações de armas

- Adiciona PE persistente, HUD, categorias de itens e regras de dano e vulnerabilidade elemental.
- Introduz modificações e maldições aplicáveis às armas, além das bancadas de Treinamento e Ritualística.
- Papéis de rituais e habilidades podem ser encontrados em baús; começa a progressão de habilidades e espaços de rituais.

[⬇️ Baixar v0.2.3](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.3/espiral-arsenal-fabric-0.2.3.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.3)

### v0.2.1 · Efeitos visuais de disparo

- Refaz as partículas para não bloquear a visão: adiciona traçadores finos, clarões discretos e impactos concentrados nos alvos.
- Atualiza os efeitos da Doze de Sangue e a trilha do Aguiar arremessável; corrige o modelo da Katana Xeno.

[⬇️ Baixar v0.2.1](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.1/espiral-arsenal-fabric-0.2.1.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.1)

### v0.2.0 · Expansão do arsenal

- Adiciona Katana Ágata, Fígora, Doze Boris, Doze de Sangue, Katana Xeno e Xenoblade.
- Implementa recuo de câmera, animação das Manoplas, disparos perfurantes, dano em área e animação do Aguiar arremessável.
- Corrige partículas, animações e integração dos modelos introduzidos na versão experimental.

[⬇️ Baixar v0.2.0](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.2.0/espiral-arsenal-fabric-0.2.0.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.2.0)

### v0.1.1 · Experimental

- Primeira implementação de disparos perfurantes da Doze Alheia e do Arcabuz, além de dano em área.
- Inicia partículas e animações de disparo; efeitos visuais ainda eram experimentais.

[⬇️ Baixar v0.1.1](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.1.1/espiral-arsenal-fabric-0.1.1.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.1.1)

### v0.1.0 · Protótipo inicial

- Primeiro protótipo jogável, com armas e modelos 3D iniciais, atributos de combate e sistema de Pontos de Esforço (PE).
- Base para Minecraft Java 1.20.1 com Fabric e Create Fabric.

[⬇️ Baixar v0.1.0](https://github.com/coffezada-cell/espiral-mod/releases/download/v0.1.0/espiral-arsenal-fabric-0.1.0.jar) · [Ver detalhes da release](https://github.com/coffezada-cell/espiral-mod/releases/tag/v0.1.0)

---

Este repositório é destinado à distribuição do mod. O código-fonte e os arquivos de desenvolvimento não são publicados aqui.

