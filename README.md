<p>Um CRUD de uma API para gestão de compras com Entity Framework Core 7 permite operações de criação, leitura, atualização e exclusão de produtos e pedidos.</p>

<p><strong>Create (Criar):</strong> Adiciona novos produtos ao catálogo e cria pedidos associando-os a produtos existentes.</p>

<p><strong>Read (Ler):</strong> Recupera a lista de produtos ou detalhes específicos, e consulta pedidos, incluindo informações dos produtos associados.</p>

<p><strong>Update (Atualizar):</strong> Atualiza informações de produtos e detalhes dos pedidos, como produto associado e data.</p>

<p><strong>Delete (Excluir):</strong> Remove produtos do catálogo, possivelmente afetando pedidos associados, e exclui pedidos específicos.</p>

<p>Utiliza-se um <code>DbContext</code> para definir tabelas e gerenciar operações com o banco de dados. As configurações de mapeamento definem chaves primárias, tipos de dados e relacionamentos entre entidades. As migrações são usadas para criar e atualizar a estrutura do banco. Os controladores da API implementam métodos para cada operação CRUD, permitindo o gerenciamento completo do sistema de compras com o Entity Framework Core 7.</p>

