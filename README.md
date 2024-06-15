# Implementação do Ubuntu Server 24.04 com VirtualBox

![Ubuntu Server 24.04](/assets/ubunto-server.jpg)

Este repositório contém um tutorial detalhado sobre a implementação de um servidor Ubuntu Server 24.04 utilizando o VirtualBox para simular o ambiente de rede. Este trabalho foi desenvolvido para fornecer um guia prático sobre a configuração e administração de servidores Linux em um ambiente virtualizado.

👉 Acesse a [Wiki](https://github.com/IsraelJorge/ubuntu-server/wiki) para mais detalhes

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Instalação do VirtualBox](#instalação-do-virtualbox)
- [Criação da Máquina Virtual](#criação-da-máquina-virtual)
- [Instalação do Ubuntu Server 24.04](#instalação-do-ubuntu-server)
- [Configuração de Serviços](#configuração-de-serviços)
- [Referências](#referências)

## Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes pré-requisitos:

- Computador com capacidade de virtualização habilitada.
- VirtualBox instalado (versão mais recente recomendada).
- Imagem ISO do Ubuntu Server 24.04.
- Conhecimentos básicos de redes e sistemas operacionais.

## Instalação do VirtualBox

1. Baixe a versão mais recente do VirtualBox no site oficial: [VirtualBox](https://www.virtualbox.org/).
2. Siga as instruções de instalação fornecidas pelo instalador.

## Criação da Máquina Virtual

1. Abra o VirtualBox e clique em "Novo" para criar uma nova máquina virtual.
2. Siga os passos do assistente, configurando o nome da máquina, tipo e versão do sistema operacional (Ubuntu Server 24.04).
3. Configure a memória RAM (recomenda-se pelo menos 2GB).
4. Crie um disco rígido virtual (recomenda-se pelo menos 50GB).
5. Finalize a criação da máquina virtual.

## Instalação do Ubuntu Server

1. Selecione a máquina virtual criada e clique em "Iniciar".
2. Escolha a imagem ISO do Ubuntu Server 24.04 como mídia de inicialização.
3. Siga os passos do instalador do Ubuntu para concluir a instalação.

## Configuração de Serviços

Após a instalação do Ubuntu Server 24.04, siga os tutoriais específicos para a configuração dos seguintes serviços:

- Apache
- BIND9
- PROFTPD
- Samba
- ISC DHCP Server
- Squid

## Referências

- [Documentação do VirtualBox](https://www.virtualbox.org/wiki/Documentation)
- [Guia de Instalação do Ubuntu Server](https://ubuntu.com/server/docs/installation)
- [Documentação do Ubuntu Server](https://ubuntu.com/server/docs)

---

Este trabalho foi desenvolvido como parte da aprendizagem prática da disciplina de Redes II, explorando a configuração e administração de servidores Ubuntu em ambientes virtuais.
