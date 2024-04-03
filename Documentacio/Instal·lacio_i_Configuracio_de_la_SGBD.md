# Instal·lació i Configuració des d'un Ubuntu 22.04

```
sudo apt-get install curl 
```
![comanda1](Imatges/1.png)
<br>
```
curl -fsSL https://packages.microsoft.com/keys/microsoft.asc | sudo gpg --dearmor -o /usr/share/keyrings/microsoft-prod.gpg
```
![comanda2](Imatges/2.jpg)
```
sudo cp /usr/share/keyrings/microsoft-prod.gpg /etc/apt/trusted.gpg.d/
```
![comanda3](Imatges/3.jpg)
<br>
```
curl -fsSL https://packages.microsoft.com/config/ubuntu/22.04/mssql-server-2022.list | sudo tee /etc/apt/sources.list.d/mssql-server-2022.list
```

![comanda4](Imatges/4.jpg)
<br>
```
sudo apt-get update
```
![comanda5](Imatges/5.jpg)
<br>
```
sudo apt-get install -y mssql-server
```
![comanda6](Imatges/update.jpg)
<br>

```
sudo ACCEPT_EULA='Y' MSSQL_PID='Developer' MSSQL_SA_PASSWORD='WeNeedABetterPassword!!!1' MSSQL_TCP_PORT=1433 /opt/mssql/bin/mssql-conf setup
```
![comanda17](Imatges/17.jpg)
<br>
```
systemctl status mssql-server --no-pager
```
![comanda15](Imatges/15.jpg)
<br>
```
curl https://packages.microsoft.com/config/ubuntu/22.04/prod.list | sudo tee /etc/apt/sources.list.d/ms-prod.list
````
![comanda16](Imatges/16.jpg)
```
sudo apt-get update
```
![comanda9](Imatges/9.jpg)
```
sudo apt-get install -y mssql-tools18 unixodbc-dev
```
![comanda10](Imatges/10.jpg)

```
sudo /opt/mssql/bin/mssql-conf set sqlagent.enabled true
```
![comanda11](Imatges/11.jpg)

```
sudo systemctl restart mssql-server
```
![comanda12](Imatges/12.jpg)

```
sudo apt-get install -y net-tools
````
![comanda13](Imatges/13.jpg)


