# Descrição do Projeto

## Estrutura de Classes para Gerenciamento de Aparelho Telefônico

Foi criado um diagrama de classes representando uma estrutura que permite gerenciar um aparelho telefônico. Nesse diagrama:

- **Classe Reprodutor Musical:** Representa a funcionalidade de reprodução de música no iPhone, com métodos como "play()", "pause()" e "stop()". Possui um atributo "playlist" para gerenciar a lista de reprodução.

- **Classe Aparelho Telefônico:** Descreve a capacidade de fazer chamadas e enviar mensagens, implementando a interface "Comunicador". Inclui métodos como "fazerLigacao()" e "enviarMensagem()" e um atributo para armazenar o número de telefone.

- **Classe Navegador na Internet:** Representa a capacidade de navegar na internet, com métodos como "navegar()" e "pesquisar()".

- **Comunicador (Interface):** Define os métodos "fazerLigacao()" e "enviarMensagem()" que são implementados pelas classes Aparelho Telefônico e Reprodutor Musical.

Essa estrutura de classe proporciona a funcionalidade básica para gerenciar contatos em um aparelho telefônico, permitindo adicionar e listar contatos, e pode ser expandida para incluir recursos adicionais ou informações de contato mais detalhadas, conforme necessário.

