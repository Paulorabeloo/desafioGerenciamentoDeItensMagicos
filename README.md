## Desafio: Sistema de Itens Mágicos
Você é um aventureiro em um mundo mágico repleto de perigos e monstros. Durante suas missões, você coleta diversos itens mágicos, cada um com seus próprios atributos e habilidades especiais. Agora, você está desenvolvendo um sistema aprimorado para gerenciar esses itens.

### Tarefa
Crie um sistema para representar um item mágico personalizado. O sistema deve permitir a criação de diferentes tipos de itens mágicos, como armas, armaduras, poções, entre outros. Cada tipo de item terá atributos específicos e contribuirá de maneiras únicas para suas aventuras.

Para isso, você deve:

1. Criar uma classe chamada ItemMagico com um construtor que recebe o tipo de item, o dano e a resistência.
2. Implementar um método chamado calcularDano que calcula o dano causado por um item durante um combate. O cálculo deve considerar o tipo de item:
- Se o tipo do item for 'arma', o dano deve ser multiplicado por 2.
- Se não for 'arma', o dano deve ser retornado como está.

3. Solicitar ao usuário a entrada para criar um item mágico. A entrada deve incluir:
- Tipo do item (por exemplo: Espada, Cajado, Arco, etc.)
- Dano do item (um número inteiro)
- Resistência do item (um número inteiro)
  
4. Imprimir os atributos do item personalizado:
- Tipo do item
- Dano do item
- Resistência do item
- Dano em combate (calculado com base no tipo do item)
  
### Entrada
- Tipo do item: Uma linha com o tipo do item (por exemplo: Espada, Cajado, Arco).
- Dano do item: Uma linha com o dano do item (um número inteiro).
- Resistência do item: Uma linha com a resistência do item (um número inteiro).
  
### Saída
- Tipo: Tipo do item
- Dano: Dano do item
- Resistencia: Resistência do item
- Dano em combate: Dano calculado durante um combate
