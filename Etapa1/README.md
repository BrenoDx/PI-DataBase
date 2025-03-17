# 🎮 FotoGames
- **Responsável pelo documento: Breno Alves**

A loja Fotogames uma pequena loja de vendas de hardware e acessórios tem 
problemas de gerenciamento do estoque na loja além de ainda fazerem todo 
atendimento em bloquinhos de notas e  inclusive notas fiscais e garantia do 
produto manualmente resultando a demora do atendimento e o excesso de 
papeis. 
Este projeto de um sistema apenas para acesso dos funcionários da loja 
oferece soluções de gestão de estoque e automatizar atividades manuais dos 
funcionários, com isso  irá permitir cadastro de novos produtos e atualizar o 
estoque incluindo entrada e saída dos itens, registros de vendas com emissões 
de notas fiscais e garantia do produto.
## 👥 Descrição dos usuários
- `Gerente` - Tem acesso a todas as funcionalidades do sistema.
- `Atendentes` - Tem acesso apenas nas funcionalidades de vendas do sistema.
## 📌 Necessidades observadas e regras de negócio
- Fornecer relatório do estoque atual.
- Garantia varia entre 6 meses a 1 ano dependendo do hardware.
- Não permitir a venda dos itens que estejam indisponível.
## 📌 Requisitos funcionais
**RF001 Cadastro de Produtos**
- **Ator:** Gerente

Descrição: A função vai permitir que o gerente cadastre, atualiza e remova produtos que estejam no estoque da loja.

**RF002 Registro de Orçamentos**
- **Ator:** Atendentes

Descrição: O atendente poderá registrar as vendas dos itens emitindo a nota fiscal e a garantia do produto com mais facilidade e rapidez no atendimento.
## Requisitos não funcionais
**RNF001 Sistema** 
* Para aproveitar os computadores parados que é pra uso dos funcionários o  
mais apropriado nesse caso seria sistema desktop

**RNF002 Autenticação** 
* Devemos implementar autenticação de usuários para os funcionários da loja 
com diferentes níveis de acesso as funcionalidades
## 💻 Telas
- **Cadastro de Produtos**

A tela vai ter nome, especificações, valor e quantidade no estoque. 
- **Registro de Orçamento**

A tela vai ter dados do cliente, descrição dos produtos, valor de cada peça e 
total do orçamento, opções de excluir, editar e imprimir orçamento. 
- **Registro de Vendas**

A tela vai ter especificação do produto, quantidade no estoque, dados do 
cliente e forma de pagamento para nota fiscal e garantia do produto. 



