# 🌐 Desafio DIO – Máquinas Virtuais no Azure

Este repositório contém a documentação e os registros do desafio da **DIO sobre Máquinas Virtuais no Azure**.
O objetivo foi colocar em prática os conhecimentos adquiridos durante o laboratório, criando e configurando uma VM no Microsoft Azure.

## Configuração da Máquina Virtual

Provedor: **Microsoft Azure**

Sistema Operacional: Windows Server 2019 Datacenter – Gen2

Região: Brazil South

Tamanho da VM: Standard B1s (1 vcpu, 1 GiB memória)

Autenticação: Usuário(dio) e senha

Armazenamento: Disco SSD Padrão de 128 GB

Rede: IP público + porta RDP (3389) liberada

## Passos Realizados

Acesse o **[Portal do Azure](https://portal.azure.com)**.

Criei um Grupo de Recursos chamado *```dio-desafio-vm```*.

Criei uma Máquina Virtual com as configurações listadas acima.

Configurei as regras de rede (NSG) para permitir acesso RDP.

Acessei a VM via Remote Desktop (RDP).

Realizei testes de conectividade e configuração inicial do Windows Server.

## Estrutura do Repositório
```bash
 dio-desafio-vm
 ┣ images
 ┃ ┣ vm-portal.png
 ┃ ┣ vm-config.png
 ┃ ┗ vm-rdp.png
 ┣ README.md
 ```

 ## Aprendizados

Entendimento prático sobre a criação de máquinas virtuais no Azure.

Configuração de rede e segurança (NSG) para acesso remoto.

Experiência com a interface do portal e boas práticas de provisionamento.

## Conclusão

O desafio proporcionou a oportunidade de consolidar os conceitos de computação em nuvem aprendidos em aula.
Com isso, foi possível criar, configurar e acessar uma máquina virtual no Azure de forma prática e documentada.