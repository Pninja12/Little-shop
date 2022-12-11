# Fantasy Battle Defense Dealer 
### Relatório

![Imagem de uma loja](https://img.freepik.com/premium-vector/little-shop-stand-pixel-art-style_475147-1401.jpg?w=2000)

### [Repositório GitHub] (https://github.com/Pninja12/Little-shop)

## Quem fez e o quê
- Paulo Silva (22206205)
    - Inicio do jogo
    - Crafting
    - Detalhes Visuais
    - Venda
- Mariana Marques (22207510)
    - Introdução dos materiais no código
    - Compra dos materiais

---

## Pontuação Extra

[ ]Interface em PyGame
[ ] Sistema de "Barter" - O NPC pode negociar com com o Jogador (contraproposta)
[X] Mais Recursos
[ ] Sistema de Crafting mais refinado
[X] Mais Items
[ ] Selling Experience (Permite ao jogador vender a valores mais altos do que o normal)
[ ] Sistema de Audio

---

## Lógica do código

1. ##### Compra de materiais
    - No começo de cada dia, o jogador tem que comprar materiais.
    - O jogo diz-lhe quanto dinheiro tem e quanto dinheiro precisa para comprar o que quer.
    - O loop da compra pára quando o jogador fica sem dinheiro ou quando escreve 'done'.

2. ##### Construção 
    - Ao sair da compra, o jogador é apresentado com um menu de o que pode fazer, e o que tem com ele naquele momento.
    - Quando escolhe que tipo quer fazer entre 'Weapon','Bow','Shield' e 'Armour', o jogador depois depara-se com os tipo de formas diferentes que ele pode fazer.
    - Após selecionar o que quer fazer, o programa verifica se o jogador tem 'experience points' e materiais necessários e começa a produção.
    - Se a produção falhar, o jogador fica sem os materiais, mas se conseguir então o programa pede ao jogador que este diga um nome e um custo para o que criou.
    - O loop acaba quando o jogador escrever 'done' ou ficar sem itens no inventário.

3. ##### Venda
    - Quando o jogador sair do menu de criação de itens, depara-se com o ecrã a dizer que os itens estão a ser vendidos com o custo que o jogador deu.

5. ##### Loop do jogo
    - O jogo só acaba quando o jogador chegar a um valor de moedas previamente estipulado ou quando não tiver moedas

4. ##### Import's
    - O "import os" é usado para apagar as linhas do terminal
    - O "import time" é usado para fazer o programa esperar algum tempo antes de apagar as linhas do terminal
    - O "import random" é usado para verificar se um item é bem sucedido ou não

5. ##### Faltas
    - O jogador pode por um custo absurdo no seu item e ganhar esse mesmo dinheiro na venda.

5. ##### Easter Egg
    - Quando um jogador fabrica a armadura de mais alto nível, aparece à frente do jogador que ele 'ascendeu'

6. ##### Informação usada de fora
    - Site [W3Schools](https://www.w3schools.com/python/python_dictionaries.asp)
    - Colegas:
        | Nome | Número | Ajuda |
        | - | - | - |
        | António Rodrigues | 22202884 | Materiais |
        | Henrique Monteiro | 22202855 | Lógica do loop "for" |
        | João Silva | 22004451 | Hint como ajuda no primeiro dia |
        | Ricardo de Almeida | 21807601 | Lógica de apagar o terminal |
        | Prof. Phil Lopes | ? | Ajuda nas classes |