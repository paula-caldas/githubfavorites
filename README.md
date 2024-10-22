
# Github Favorites

Essa página é um projeto de favoritos do GitHub, onde os usuários podem buscar perfis do GitHub, salvar seus favoritos e visualizar informações básicas como repositórios e seguidores.




## Funcionalidades


1. **Busca de Usuário do GitHub**:
   - O usuário pode buscar perfis do GitHub inserindo um nome de usuário e clicando no botão "+".

2. **Validação de Usuário Existente**:
   - Antes de adicionar, a página verifica se o usuário já está na lista de favoritos para evitar duplicatas.

3. **Validação de Usuário Válido**:
   - A página verifica se o usuário do GitHub existe, exibindo uma mensagem de erro caso o perfil não seja encontrado.

4. **Exibição de Informações do Usuário**:
   - Para cada usuário adicionado, são exibidas as seguintes informações:
     - Foto de perfil.
     - Nome.
     - Nome de usuário (login).
     - Quantidade de repositórios públicos.
     - Quantidade de seguidores.

5. **Remoção de Usuário Favorito**:
   - O usuário pode remover perfis da lista de favoritos clicando no botão de "remover" (`×`).

6. **Persistência dos Favoritos**:
   - Os favoritos são salvos no `localStorage`, permitindo que a lista persista mesmo após recarregar ou fechar a página.

7. **Atualização Dinâmica da Tabela**:
   - A tabela com a lista de favoritos é atualizada automaticamente após adicionar ou remover um usuário, sem a necessidade de recarregar a página.

8. **Acessibilidade**:
    - A página inclui elementos ocultos para leitores de tela, como a classe `sr-only` para acessibilidade.
## Aprendizados

O que você aprendeu construindo esse projeto? 


1. **API - Interface de Programação de Aplicação**:
   - A página interage com a API do GitHub para buscar dados de usuários, como login, repositórios e seguidores.

2. **Estrutura de Tabela**:
   - Exibição de dados organizados em uma tabela HTML com tags como `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, e `<td>`.

3. **Classes e Construtores em JavaScript**:
   - Uso de classes para organizar o código e construtores para inicializar a página.

4. **Herança com `extends` e `super`**:
   - Aplicação de herança em classes para reutilizar funcionalidades em subclasses.

5. **Atualização da Tabela**:
    - Função `update()` para atualizar a tabela após modificações nos dados (adicionar ou remover usuários).

6. **Criação de Elementos HTML Dinamicamente**:
    - Uso de `document.createElement()` para criar linhas da tabela dinamicamente.
7. **Deletar Usuários**:
    - Implementação de um botão para deletar usuários, com confirmação antes da exclusão.

8. **Imutabilidade em JavaScript**:
    - Aplicação do princípio da imutabilidade ao criar novos arrays filtrados, sem alterar o original.

9. **Armazenamento de Dados com LocalStorage**:
    - Persistência de dados do usuário no navegador usando `localStorage`, permitindo salvar e carregar informações localmente.

10. **Comunicação com a API do GitHub**:
    - Integração com a API do GitHub para buscar informações de usuários, como nome, login, repositórios, e seguidores.


## Screenshots

![App Screenshot](https://i.imgur.com/1bCVbn2.png)


## Demonstração

https://github.com/user-attachments/assets/02a83ea2-dc62-4d9e-b744-b87b1adf3854

