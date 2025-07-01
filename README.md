# Gerenciador de Clubes e Jogadores de Futebol

Um sistema CRUD (Create, Read, Update, Delete) simples para gerenciar informações de clubes e jogadores de futebol, desenvolvido em Python com interface gráfica Tkinter e banco de dados SQLite.

## Funcionalidades

* **Gerenciamento de Clubes:**
    * Adicionar novos clubes (Nome, País, Ano de Fundação).
    * Visualizar a lista de clubes existentes.
* **Gerenciamento de Jogadores:**
    * Adicionar novos jogadores (Nome, Posição, Nacionalidade, Data de Nascimento).
    * Associar jogadores a clubes existentes através de um menu de seleção.
    * Visualizar a lista de jogadores com seus respectivos clubes.
    * Atualizar dados de jogadores.
    * Excluir jogadores.
* **Interface Intuitiva:**
    * Interface gráfica amigável baseada em Tkinter.
    * Menu de cabeçalho com opções de Arquivo, Editar, Exibir e Ajuda.
    * Janela separada para gerenciamento de clubes.

## Como Rodar o Projeto

### Pré-requisitos

* Python 3.x instalado.

### Passos

1.  **Clone ou baixe** este repositório para o seu computador.
2.  **Navegue** até a pasta do projeto no seu terminal.
3.  **Execute** o arquivo principal:
    ```bash
    python main.py
    ```
4.  Ao iniciar a aplicação, você pode primeiro usar a opção "Gerenciar Clubes" no menu "Arquivo" ou o botão "Gerenciar Clubes" na interface para adicionar alguns clubes.
5.  Em seguida, adicione jogadores e associe-os aos clubes criados.

## Estrutura do Projeto

* `main.py`: Contém a lógica da interface gráfica (Tkinter) e a interação com o banco de dados.
* `database.py`: Contém a lógica de conexão e operações CRUD com o banco de dados SQLite.
* `futebol.db`: O arquivo do banco de dados SQLite (será criado automaticamente na primeira execução, se não existir).

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Autor

@ghostc0der
