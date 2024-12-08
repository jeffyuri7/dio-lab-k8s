# Laboratório Bootcamp Azure Advanced - DIO

Como atividade do laboratório eu implantei o mesmo exercício na minha máquina e em um cluster na minha assinatura do Azure. Abaixo algumas imagens dos meus testes.

## Imagem no Docker meu repositório do Docker Hub
Subi a minha imagem para um repositório do Docker Hub. Além disso fiz os testes executando a imagem diretamente do repositório.

![image](https://github.com/user-attachments/assets/b55bf804-64eb-4293-a7d1-66b50da9edd3)

![image](https://github.com/user-attachments/assets/647e714e-b126-46b6-a5f3-2e34bdd3690f)

## Cluster Kubernets - Azure Kubernets Service (AKS)
Subi um cluster na Azure para testar a solução. Para isso alterei o deployment.yml para baixar a imagem do meu repositório, como pode ser observado abaixo:

![image](https://github.com/user-attachments/assets/c1d5914a-2aca-40ed-a322-b5822e5336ab)

Após isso criei um cluster na Azure, como pode ser observado abaixo:

![image](https://github.com/user-attachments/assets/a526a6a1-0004-4c82-99c2-7441da2031c5)

![image](https://github.com/user-attachments/assets/be2a9aa7-0c78-45cb-8d1b-7bfefa7204b2)

Obtendo informações do serviço:

![image](https://github.com/user-attachments/assets/efee1b58-2ce9-47ce-b499-24520c1a9ae4)

Conectando no LoadBalance:

![image](https://github.com/user-attachments/assets/c1af6409-997d-45a3-afb1-e24cd71c2095)

Pods em execução:

![image](https://github.com/user-attachments/assets/7238b099-c1d5-4fb9-9bf4-c85cb1fb67b7)

Conjuntos de Réplicas:

![image](https://github.com/user-attachments/assets/e193c2f9-ac5e-493c-9eef-79ba36abe9f4)

Projeto foi por: __Jefferson Yuri__
