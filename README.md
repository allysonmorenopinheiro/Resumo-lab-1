# Resumo-lab-1

Este resumo contém as lições aprendidas no modulo #01 da lab da Dio, passo a passo. 

 -> Passo 1: Acesse o Portal do Azure

1. **Acesse o portal Azure:** Vá para [portal.azure.com](https://portal.azure.com).
2. **Faça login:** Utilize suas credenciais.

-> Passo 2: Criar um novo recurso

1. **Clique em "Criar um recurso":** No canto superior esquerdo do portal, clique em "Criar um recurso".
2. **Procure por "Banco de Dados SQL":** Na caixa de pesquisa, digite "Banco de Dados SQL" e selecione o resultado correspondente.

-> Passo 3: Configurar o Banco de Dados SQL

1. **Escolher a assinatura:** Se você tiver várias assinaturas, selecione a que deseja usar.
2. **Criar um novo grupo de recursos** ou selecionar um existente: Um grupo de recursos é um contêiner que mantém os recursos relacionados.
3. **Definir o nome do banco de dados:** Insira um nome único para o seu banco de dados.
4. **Selecionar o servidor:** Você pode criar um novo servidor ou usar um existente. Se for criar um novo:
   - **Nome do servidor:** Escolha um nome exclusivo para o servidor.
   - **Localização:** Selecione a região onde deseja hospedar o servidor.
   - **Administração:** Defina um nome de administrador e uma senha.

-> Passo 4: Configurar o desempenho

1. **Escolher um plano de preços:** O Azure oferece várias opções de desempenho, como o plano **DTU** (Database Transaction Unit) ou **vCore**. Selecione a opção que melhor atende às suas necessidades.
2. **Configurações adicionais:** Você pode configurar opções como backups automáticos, alta disponibilidade, etc., com base em suas necessidades.

-> Passo 5: Revisar e criar

1. **Revisar as configurações:** Verifique se todas as informações inseridas estão corretas.
2. **Clique em "Criar":** O Azure começará a provisionar sua instância de banco de dados.

-> Passo 6: Conectar-se ao Banco de Dados

1. **Acesse o banco de dados:** Depois que o banco de dados estiver criado, você poderá vê-lo no portal.
2. **Configurar regras de firewall:** Para permitir que seu aplicativo ou outras máquinas acessem o banco de dados, você precisará configurar regras de firewall. Vá para a configuração do servidor e adicione os endereços IP que devem ter acesso ao banco de dados. 
3. **Utilizar ferramentas de gerenciamento:** Você pode se conectar ao banco de dados usando o Azure Data Studio, SQL Server Management Studio (SSMS) ou qualquer outra ferramenta de banco de dados que suporte conexões SQL.

-> Lembrete: 

- **Custos:** Fique atento aos custos, já que o Azure SQL Database é um serviço pago baseado em uso.
- **Segurança:** Considere habilitar funcionalidades adicionais de segurança, como autenticação multifator, criptografia e auditoria.
- **Backup:** Estabeleça uma rotina de backups e restaurações regular, se necessário.

