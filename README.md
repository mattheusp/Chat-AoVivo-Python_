![Bate papo em tempoo real](https://i.imgur.com/xJ1UP5P.png)


# Aplicação de Bate-Papo em Tempo Real com Flask e Socket.IO


## Visão geral

Esta é uma aplicação simples de bate-papo em tempo real construída usando Python, Flask e Socket.IO. A aplicação permite que os usuários criem ou participem de salas de bate-papo e participem de conversas em tempo real.


## Demostração do projeto

![GIF do resultado](assets/gif/utilizando%20a%20aplicação.gif)


## Ferramentas utilizadas:
     - Flask
     - Flask-SocketIO
     - Python 3.x

## Funcionalidades

1. **Página Inicial:**
   - Os usuários podem inserir seus nomes e escolher entre criar uma nova sala ou participar de uma existente.
   - Códigos de sala são gerados aleatoriamente para novas salas.
   - Mensagens de erro são exibidas para entradas incompletas ou inválidas.

![pagina inicial](assets/imgs/1.png)

2. **Sala de Bate-Papo:**
   - Os usuários são redirecionados para uma sala de bate-papo onde podem ver mensagens de outros participantes.
   - A sala de bate-papo é identificada por um código exclusivo.
   - Os usuários podem enviar e receber mensagens em tempo real.

![sala de bate papo](assets/imgs/2.png)

3. **Comunicação em Tempo Real:**
   - Utiliza o Flask-SocketIO para permitir comunicação bidirecional em tempo real entre o servidor e os clientes.
   - As mensagens são transmitidas para todos os participantes na mesma sala.

![comunicação em tempo real](assets/imgs/3.png)

4. **Conexão/Desconexão do Usuário:**
   - Notifica quando um usuário entra ou sai da sala de bate-papo.
   - Atualiza a contagem de membros atuais na sala.

![conexão/desconexão do usuário](assets/imgs/4.png)

## Como utilizar a aplicação?

1. Clone o repositório:

   ```bash
   git clone https://github.com/mattheusp/Chat-AoVivo-Python_


## Como funciona

1. ### recursos
     - escolha a quantidade de produtos
     - adicionar produtos ao carrinho
     - adicionar endereço de entrega (código postal, bairro, número)
     - enviar os produtos escolhidos para o WhatsApp da empresa
     - taxa de entrega


## Estrutura de Arquivos

- main.py: Script principal da aplicação.
- templates/home.html: Modelo HTML para a página inicial.
- templates/room.html: Modelo HTML para a sala de bate-papo.
- requirements.txt: Lista de dependências Python.

## Contato ✉️

- E-mail: mattheusp382@gmail.com
- LinkedIn: [Mattheus-Pereira](https://www.linkedin.com/in/mattheuspereira/)
- Portfólio: [mtp-dev.com](https://mtpdev.com.br/)

## Contribuição 🤝

Se você quiser contribuir com um projeto ou encontrar um problema, sinta-se à vontade para abrir um novo problema ou enviar uma solicitação pull. Qualquer contribuição é bem-vinda!

## Licença📄

Este portfólio está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).