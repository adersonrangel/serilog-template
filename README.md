#Serilog Template






##Docker Install for Seq
Run this command in your platform

'''
docker run -d --restart unless-stopped --name seq -e ACCEPT_EULA=Y -v /mnt/c/Logs:/data -p 8081:80 datalust/seq:latest

'''