# demoprojectforpractice
Here are some steps to host your project on the server or on the cloud (AWS,GCP).
For Installing and hosting website on webserver in Ubantu

apt-get update
apt-get install nginx -y
make a folder for copy our web packages.
then copy all files in zip or normal files with command wget url.


then install unzip package with command -"apt-get install unzip".

and move all files in the /var/www/html/ folder.


Here are some command if you use amazon linux to host your project 
sudo su -
yum update -y
yum install -y httpd
systemctl status httpd
mkdir temp
cd temp
wget https://www.free-css.com/assets/files...
unzip complex.zip
cd complex
ls -lrt
mv * /var/www/html
systemctl enable httpd
systemctl start httpd~
