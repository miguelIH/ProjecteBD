# Connectar-se i manipular
Aquí podrem veure com poder connectar-nos a la base de dades escollida i després com poder modificar (SELECT, UPDATE, INSERT, DELETE)

- Aqui tenim que entrar a la aplicacio de desktop 'SQL Server Managment Studio' i fer Login.

![Imatge_Taula](CONFIGURACIO/hola21.jpg)

- Una vegada fet aixo tenim que anar a databases i fer click dret, una vegada fet aixo li donem a 'New Database...'.

![Imatge_Taula](CONFIGURACIO/1.jpg)

- Seguidament estarem a una pantalla que on posa 'database name' posem el nom que voldrem. En el nostre cas posarem 'Botiga Informatica'.

![Imatge_Taula](CONFIGURACIO/2.jpg)

- Despres de posar el nom tornarem a donar click dret i li donarem a 'New Query' on posarem els '.sql' de la database importada.

![Imatge_Taula](CONFIGURACIO/3.jpg)

Posem la informacio de Botiga Informatica

![Imatge_Taula](CONFIGURACIO/4.jpg)

Posem la informacio de Botiga Informatica

![Imatge_Taula](CONFIGURACIO/5.jpg)


Una vegada fet aixo manipularem una mica la base de dades.
- Fem un SELECT per poder veure la informacio de la taula 'Producto'. 

![Imatge_Taula](CONFIGURACIO/6.jpg)

- Fem un altre SELECT una mica més elaborat per veure la informació de les taules 'Productes', 'Fabricants' i 'Preus'.

![Imatge_Taula](CONFIGURACIO/7.jpg)

- Una vegada fet aixo fem un insert de la marca 'Apple' a la taula producte.

![Imatge_Taula](CONFIGURACIO/8.jpg)

Aqui veiem com ha quedat

![Imatge_Taula](CONFIGURACIO/9.jpg)

- Despres hem realitzat uns 'UPDATES' 

![Imatge_Taula](CONFIGURACIO/10.jpg)

Comprovació

![Imatge_Taula](CONFIGURACIO/11.jpg)

- Per ultim fem uns delete i seguidament mirem com ha quedat 

![Imatge_Taula](CONFIGURACIO/12.jpg)

Com queda

![Imatge_Taula](CONFIGURACIO/13.jpg)

# Encriptacio
- Aqui hem creat la clau simetrica per encriptar i desencriptar informació

![Imatge_Cifrat](CONFIGURACIO/CIFRADO1.jpg)

- Aqui podem veure la comprovació

![Imatge_Cifrat2](CONFIGURACIO/CIFRADO2.jpg)

# Creacio d'usuaris
- Creem un usuari amb login, i amb el permís d'accedir a l'esquema dbo
![Imatge_Cifrat1](CONFIGURACIO/USUARI1.jpg)
<br>
- Comprovem que s'ha creat l'usuari
![Imatge_Cifrat2](CONFIGURACIO/USUARI2.jpg)
- Afegim l'usuari base al grup db_datareader
![Imatge_Cifrat3](CONFIGURACIO/USUARI3.jpg)
- Repetim proccés amb l'usuari db_datawriter 
![Imatge_Cifrat4](CONFIGURACIO/USUARI4.jpg)


