# Soru-1:
httpd:alpine imajından detached bir container yaratınız.
docker run --name soru1 -d httpd:alpine

# Soru-2:
Container'ları listeleyiniz. httpd container'ı durdurunuz yenidan başlatınız.
docker container list
CONTAINER ID        IMAGE               COMMAND              CREATED             STATUS              PORTS               NAMES
b89986304977        httpd:alpine        "httpd-foreground"   21 minutes ago      Up 21 minutes       80/tcp              apache

# Soru-3:
 Az önce yarattığınız apache isimli container loglarını inceleyiniz.
docker container logs apache
 
AH00558: httpd: Could not reliably determine the server's fully qualified domain name, using 172.17.0.3. Set the 'ServerName' directive globally to suppress this message
AH00558: httpd: Could not reliably determine the server's fully qualified domain name, using 172.17.0.3. Set the 'ServerName' directive globally to suppress this message
[Tue Mar 09 22:11:14.947425 2021] [mpm_event:notice] [pid 1:tid 140708077747528] AH00489: Apache/2.4.46 (Unix) configured -- resuming normal operations
[Tue Mar 09 22:11:14.947448 2021] [core:notice] [pid 1:tid 140708077747528] AH00094: Command line: 'httpd -D FOREGROUND'

# Soru-4:
Az önce yarattığınız apache container web arayüzünde docker volume kullanmadan Hi there. I have changed this. Well done to me :) yazdırınız.

# Soru-5:
apache isimli container'ı `/usr/local/apache2/htdocs` dizinini bit docker volume'a bağlayınız.

# Soru-6:
Az önceki apache isimli containerı siliniz.
