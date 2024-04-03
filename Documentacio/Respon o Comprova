1.  Un cop realitzada la instal·lació realitza una securització de la mateixa. Quin programa realitza aquesta tasca? Realitza una securització de la instal·lació.

2.  Quines són les instruccions per arrancar / verificar status / apagar servei de la base de dades del SBGB escollit a nivell sistema operatiu?
      Arrancar el servei: sudo systemctl start mysql-server.service
      Verificar stat: sudo systemctl status mysql-server.service
      Apagar el servei: sudo systemctl stop mysql-server.service

3.  A on es troba i quin nom rep el fitxer de configuració del SGBD escollit?
      /var/opt/mssql/mssql.conf

4.  A on es troben físicament els fitxers de dades (per defecte). Com ho has sabut?
      /var/opt/mssql/data   link

5.  El servei de SGBD escollit en quins ports escolta. Quina modificació/passos caldrien fer per canviar aquest port a un altre per exemple? Important: No realitzis els canvis. Només indica els passos que faries.
      Mysql server escolta per el port 1443.
      Mitjançant aquesta comanda “sudo nano /var/opt/mssql/mssql.conf”, podem veure per quin port està escoltant el nostre servidor, desde aquest arxiu tenim que buscar l’apartat dels ports i canviar el port per el qual està escoltant. Un cop canviat tenim que guardar l’arxiu i reiniciar el servei amb aquesta comanda “sudo systemctl restart mysql-server.service”.

IMATGEEEEE

6. Quin tipus de SGBD? (Relacional, no relacional, graf, document,....)
	MySQL Server es un sgbd relacional.
