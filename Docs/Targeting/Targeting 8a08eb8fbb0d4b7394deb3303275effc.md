# Targeting

## **Introdução ao Targeting**

O Targeting é uma ferramenta poderosa para automatizar a seleção de alvos e as ações do seu personagem em um jogo. Com o Targeting ativado, você pode configurar perfis personalizados para diferentes situações de caça e priorizar ações com base em uma variedade de critérios.

## **Ativando o Targeting**

Para começar a usar o Targeting, siga estes passos simples:

1. **Acesse o Targeting**: Navegue até a seção de Targeting nas configurações do seu jogo.
2. **Ative o Targeting**: Certifique-se de habilitar o Targeting para começar a configurar seus perfis e prioridades de ataque.

![Untitled](Targeting%208a08eb8fbb0d4b7394deb3303275effc/Untitled.png)

## **Criando Perfis de Targeting**

Os perfis de Targeting permitem salvar e gerenciar suas configurações para cada sessão de caça. Você pode criar diferentes perfis e ativá-los conforme necessário. Eis como:

1. **Criação de Perfis**: Crie um novo perfil de Targeting para cada tipo de caça que você realizará.
2. **Ativação de Perfis**: Escolha qual perfil deseja utilizar e ative-o para que suas configurações entrem em vigor.

![Untitled](Targeting%208a08eb8fbb0d4b7394deb3303275effc/Untitled%201.png)

## **Prioridades de Targeting**

Ao ativar o Targeting, você pode definir as seguintes prioridades para determinar quem o bot deve atacar primeiro em um grupo de monstros:

- **Heath:** Atacar o monstro com menor vida.
- **Proximity:** Atacar o monstro mais próximo.
- **Danger:** Atacar o monstro mais perigoso.
- **Stick:** Priorizar um alvo até ele sumir, invés de atacar todos.

## **Opções de Targeting**

Existem várias opções disponíveis para personalizar o comportamento do bot em relação aos alvos:

- **Target must be reach:** O bot só realizará a ação quando alvo for alcançável, ou seja, se tiver atrás de uma porta, ele não vai atacar .
- **Target must be shoot:** O bot só atacará quando for possível usar um ataque de longa distância.
- **Ignore creature type:** A criatura será alvo, independente do seu tipo (NPC, player, monster)

## **Lista de Criaturas**

Você pode especificar quais monstros o bot deve atacar adicionando-os a uma lista.

![Untitled](Targeting%208a08eb8fbb0d4b7394deb3303275effc/Untitled%202.png)

## **Editando Criaturas**

![Untitled](Targeting%208a08eb8fbb0d4b7394deb3303275effc/Untitled%203.png)

**Name**: nome do monstro, tem quer respeitar as letras maiúsculas e minúsculas.

caso o monstros conter level no nome, ou alguma informação não fixa, você pode usar o caractere *. Exemplo:

O OtPokemon contém o nível do pokemon no nome:

![Untitled](Targeting%208a08eb8fbb0d4b7394deb3303275effc/Untitled%204.png)

Para atacar o Bellsprout, invés de por Bellsprout [6] no name, você pode por Bellsprout*. Assim atacara qualquer Bellsprout, independente do nível.

Caso queira atacar todo os pokemons ao seu redor, você pode usar o  caractere *, ou a palavra  ALL.

**Count**:  Atacar somente quando um determinado número de criaturas estiver presente.

Exemplo da imagem: ataque só quando tiver 1 ou mais monstros

**HP Range**: Atacar apenas quando o monstro estiver dentro de uma faixa específica de vida.

Exemplo da imagem: ataque só quando tiver com a vida entre 0% e 100%. Ou seja, ataque independente da vida.

**Danger**: O valor de perigo dessa criatura. Quanto maior, mais perigoso.

**Avoidar(Evitar):** Evite que seu personagem fique de frente ou diagonal com o alvo.

No Avoidance: não precisa evitar posições

Avoid Front: Evite ficar de frente com o alvo

Avoid Diagonal: Evite ficar na diagonal do alvo

**Stance(Posição)**:  Informa se o personagem deve chegar perto do alvo, ficar longe ou ficar seguindo o mesmo.

No Movement: Nenhum movimento

Reach: chegar perto

Chase: Perseguir(Follow)

keep Away: Ficar longe

**Distance(Distancia)**: Distancia que o personagem deve permancer do monstro. Funciona apenas para quando o tipo de Stance(Posição) estiver como keep Away(Ficar longe).

**Action:** ação que deve ser tomada ao avistar o alvo

Attack: Atacar

Follow: Seguir

Ignore: ignorar

**Mode(Modo):** Alguns OtClient tem a configuração de como o personagem de deve se comportar e usar suas habilidades… Com foco em ataque, defesa ou equilibrado.