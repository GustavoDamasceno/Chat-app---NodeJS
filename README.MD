# Chat - Real time

1. Introdução
2. Dependências
3. Funcionalidade


## 1. Introdução

Chat em tempo real, utilizando **nodeJS**, **express** e  **socket.io**. Como o sistema não está conectado a um banco de dados. Sendo assim, ao reiniciar o servidor... os dados serão perdidos.


## 2. Dependências

* NodeJS
* Express
* Socket.io

### NodeJS

Pode ser definido como um ambiente de execução Javascript server-side. O que significa que com o nodeJS é possível criar aplicações Javascript para rodar como uma aplicação standalone em uma máquina, não dependendo de um browser para a execução. Seu objetivo é ajudar programadores na criação de aplicações de alta escabilidade, com códigos capazes de manipular dezenas de milhares de conexões simultâneas, numa única máquina física. O nodeJS é baseado ni interpretador V8 Javascript Engine (interpretador de Javascript open source implementado pelo Google em C++ e utilizado pelo Chrome). Foi criado em 2009, e seu desenvolvimento é mantido pela fundação Node.JS em parceria com a Linux Foundation.


### Express

É um framework para construção de aplicações web para nodeJS. Ele simplifica o processo de criação do servidor que já está disponível no Node.


### Socket.io

Traz uma forma de conexão direta do browser do cliente com o servidor de aplicação. A biblioteca funciona através de eventos, ou seja, o servidor ou o cliente irão disparar eventos para que haja respostas de uma das partes.

  ![](https://arquivo.devmedia.com.br/REVISTAS/front_end/imagens/edicao9/4/1.png)

   De certa forma, vamos usar dois métodos muitos básicos do módulo, que são o emit e o on. Um serve para efetuar a emissão do evento e o outro para receber a resposta do mesmo. Cada um dos lados da aplicação, portanto, terão a biblioteca Socket.IO adicionada.

   Além de permitir a troca direta de mensagens entre dois dispositivos, o Socket.IO também permite o broadcast de mensagens, o envio de um evento a todos os outros usuários conectados. O broadcast pode ser tanto do cliente quanto do servidor, conforme demonstrado na Figura

   ![](https://arquivo.devmedia.com.br/REVISTAS/front_end/imagens/edicao9/4/2.png)

   Quando o usuário acessar a página, um socket é criado com o servidor e é através deste socket que é realizada a troca de mensagens entre um cliente e um servidor. Este, por sua vez, pode tanto emitir um evento para um único Socket como para todos os sockets conectados a ele, o que chamamos de broadcast de mensagem.



## 3. Funcionalidade


![](https://pbs.twimg.com/media/EBPyd6aXUAAeAAl?format=jpg&name=large)


![](https://pbs.twimg.com/media/EBPy6N7WkAMJaTj?format=png&name=900x900)


![](https://pbs.twimg.com/media/EBPyd6bWwAIGvKO?format=jpg&name=large)

