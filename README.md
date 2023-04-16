# Introdução
Este documento tem como objetivo detalhar a ideia de Gonçalo Sousa em centralizar uma ferramenta de ticketing, configuration management database (CMDB) e password management\
PacketDB – PAssword ticKET cmDB – Nome ainda em pensamento

# Objectivo
O objetivo desta ferramenta é agilizar e simplificar o dia-a-dia de um funcionário que trabalhe na área de IT ao centralizar 3 soluções (ticketing, CMDB, Password management) em apenas numa solução, em vez de andarmos a saltar de página para consultar informação em apenas numa página web.

# Visualização
A ferramenta seria absolutamente costumizavel (se o cliente quiser adicionar um campo que assim seja). Com as devidas restrições/roles, os utilizadores podem editar os campos e visualizar as 3 soluções.

## Password Management
O core seria adicionar 8 campos, Titulo, IP, FQDN, Utilizador, Password, URL, Descrição e Tags. Esta solução seria feita em Folder Tree com as devidas pastas e um espaço reservado ao utilizador para colocar as suas credenciais de sites e/ou utilizadores de servidor. A configuração das entradas será herdada pela pasta. E um quicksearch para faciliatar. Por exemplo:\
![alt text](pwd.png "Password Management Scratch")\

Legenda:
1 – Butões para editar as pastas (eliminar, criar, etc.)\
2 – Onde se pode ver as pastas, e ao clicar vai aparecer as entradas no 3\
3 – Lista de entradas existentes com informação básica, ao clicar nelas podemos ver o 4\
4 – Onde contem a informação destas entradas\
5 – Onde se pode editar a entrada (editar, adicionar campos)\
6 – Onde se pode eliminar e criar entradas.\

## CMDB
Um espaço para fazer inventario das infraestruras, seja VM, Aplicações URL, Switches, Routers, etc.\
Este espaço podesse adicionar manualmente a informação e costumizar os campos consoante a necessidade. Num formato semelhante a solução anterior, “Folder Tree”.\
![alt text](cmdb.png "CMDB")

## Ticketing
Changes, Incidents e Requests.\
Este espaço também terá um espaço de Wiki onde se pode documentar vários incidentes e changes e associar os mesmos a documentação\
Apenas se pode abrir ticket com a indicação do recurso afetado:\
![alt text](ticket.png "Ticketing")
