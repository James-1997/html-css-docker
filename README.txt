# AV1 DE DESENVOLVIMENTO DE SOFTWARE - QUESTÃO 1:

## Membros da equipe:
* Robson James dos Reis Silva Júnior - Matrícula: 202051531991
-> [Robson James - GitHub](https://github.com/James-1997)
-> [Robson James - LinkedIn](https://www.linkedin.com/in/robson-james-44a633127/)

* Talita Gomes Santos - Matrícula: 202051847697
-> [Talita Gomes - GitHub](https://github.com/talitagomess)
-> [Talita Gomes - LinkedIn](https://www.linkedin.com/in/talita-gomes-24078a172/)

## Passo a Passo como rodar o HTML no servidor nginx através do Docker:

1) Descompacte a pasta
2) Entre na pasta *'questão-projeto-intercursos'*
3) Abra o terminal, insira o seguinte comando e der enter:
Commando: 
```
docker run -it -d -p 8080:80 --name questaoprojetointercursos -v ~/questão-projeto-intercursos/:/usr/share/nginx/html nginx
```
4) Abra o navegador e coloque na barra de url:
> localhost:8080/
ou
> 0.0.0.0:8080/

5) Espera-se que seja mostrado o HTML customizado da equipe.