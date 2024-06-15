# creating_EC2_instance

## 1. Configuração da instância EC2
- acesse o Console da AWS e navegue até o serviço EC2; 
- crie uma nova instância EC2 usando a imagem Amazon Linux 2; 
- escolha o tipo de instância com base em suas necessidades de recursos

  ![](https://github.com/cleverson0803/creating_EC2_instance/blob/main/Inst%C3%A2ncia_EC2.png)

 ## 2. Conexão via SSH
- após a instância ser criada, use a chave privada para conectar via SSH;
- execute os comandos necessários para acessar o terminal da instância.
  ! [](https://github.com/cleverson0803/creating_EC2_instance/blob/main/Connect_to_instance.png)

## 3. Gerenciando o armazenamento
- explore as opções de armazenamento oferecidas pelo Amazon EC2; 
- crie um novo volume Elastic Block Store (EBS) com um tamanho de sua escolha; 
- anexe o volume à sua instância EC2.

 ## 4. Formatando e montando o volume
- formate o volume recém-criado usando um sistema de arquivos de sua escolha;
- monte o volume em um diretório específico em sua instância.
![](https://github.com/cleverson0803/creating_EC2_instance/blob/main/EBC.png)

## 5. Criação de arquivos
- crie um arquivo de texto simples usando o editor de sua preferência;
- salve esse arquivo no volume montado.
![](
