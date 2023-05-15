# Notizen


## MSSQL:

docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=ThePassword" -e "MSSQL_PID=Express" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest

scp /mnt/c/Users/michael.biro/Downloads/AdventureWorks2019.bak michael@192.168.56.145:~/
docker cp AdventureWorks2019.bak 7c114dae6893:/tmp


