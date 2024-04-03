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
![comanda6](Imatges/6.jpg)
<br>

sudo ACCEPT_EULA='Y' MSSQL_PID='Developer' MSSQL_SA_PASSWORD='WeNeedABetterPassword!!!1' MSSQL_TCP_PORT=1433 /opt/mssql/bin/mssql-conf setup


systemctl status mssql-server --no-pager


curl https://packages.microsoft.com/config/ubuntu/22.04/prod.list | sudo tee /etc/apt/sources.list.d/ms-prod.list


sudo apt-get update


sudo apt-get install -y mssql-tools18 unixodbc-dev


sudo /opt/mssql/bin/mssql-conf set sqlagent.enabled true


sudo systemctl restart mssql-server


sudo apt-get install -y net-tools



