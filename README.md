# Desafio de Laboratório: Criando Máquinas Virtuais no Azure

Neste repositório, está documentado o processo de criação, configuração e teste de uma máquina virtual através do Microsoft Azure.

## Criação da Máquina Virtual

Dentro da categoria de serviços gratuitos na plataforma Microsoft Azure, foi selecionada a opção de criar uma máquina virtual, com o sistema operacional de escolha do Ubuntu Server e utilizando o plano Azure for Students.

## Configuração

Como a intenção foi criar uma máquina de teste, foram selecionadas opções básicas, com a versão 22.04 do Ubuntu Server. Inicialmente houve um erro na criação por conta das regiões permitidas pelo plano, porém após verificar os servidores disponíveis, um adequado foi escolhido e o *deployment* foi realizado.

![alt text](https://github.com/KenzoWVY/resumo-do-lab-azure-vm/blob/main/images/deployed.PNG "Deployed")  


## Conexão

Através do endereço IP e da chave de segurança fornecidos, uma conexão foi estabelecida com a máquina pela linha de comando com o uso do comando ssh:

![alt text](https://github.com/KenzoWVY/resumo-do-lab-azure-vm/blob/main/images/sshConnection.png "Conexão ssh")  

O servidor nginx foi instalado e, após habilitar a escuta da porta 80 no Microsoft Azure, foi possível acessar o site pelo navegador:

![alt text](https://github.com/KenzoWVY/resumo-do-lab-azure-vm/blob/main/images/serverPage.png "Conexão nginx")

## Conclusão

Através dos conhecimentos adquiridos durante as aulas, foi possível estabelecer uma máquina virtual em nuvem pelo Microsoft Azure, expandindo meu conhecimento sobre a plataforma e sobre computação em nuvem em geral.
