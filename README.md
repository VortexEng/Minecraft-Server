# O que é
Uma forma de criar um server de minecraft usando docker com playit.gg, permitindo uma forma barata e segura de se jogar, permitindo o crossplay entre Java e Beadrock.


# Requisitos
1. Docker
2. Um computador com no minimo 8gb de ram
3. Uma conta no https://playit.gg

# Instruções

## Configurando o container
1. Clone esse repositorio no lugar de sua escolha.
```cmd
git clone https://github.com/VortexEng/Minecraft-Server.git
```

2. Acesse a pagina de agente do playit.gg
3. Clique em Add agent
4. Escolha a opção Docker e nomeie seu agente 
5. renomeie o arquivo .env-exemple para .env
6. Colete a Secret Key presente no exemplo de Docker Compose do playit e coloque no seu arquivo .env
7. rode o container usando o aplicativo docker desktop ou use o comando docker compose up -d

## Configurando o playit.gg

### Java
1. Vá para a aba Tunnels do playit e clique em new tunnel
2. Nomeie o tunnel
3. No tipo do tunnel escolha o tipo minecraft Java
4. escolha sua regiao
5. Afilie o tunnel ao seu agente
6. Na parte Origin Config apenas clique em next
7. Clique em Create tunnel
Pronto temos o tunnel java criado, seus amigos podem entrar no jogo
> [!WARNING]
> Note que o playit gera o endereço para você compartilhar

### Beadrock
1. Vá para a aba Tunnels do playit e clique em new tunnel
2. Nomeie o tunnel
3. No tipo do tunnel escolha o tipo minecraft Beadrock
4. escolha sua regiao
5. Afilie o tunnel ao seu agente
6. Na parte Origin Config apenas clique em next
7. Clique em Create tunnel
Pronto temos o tunnel Beadrock criado, seus amigos podem entrar no jogo
> [!WARNING]
> No Beadrock é necessario a Porta e o endereço para acessar o servidor
> Note que o playit gera o endereço para você compartilhar
