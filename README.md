# How-to-Back-Up-OpnProject

# To BackUp Open Project we need some prerequist environment

# 1.Need to install OpenProject again

# Note: The Open Project and postgress versiosn should be same As the Main OpenPrject server.

## FOR INSTALL OPENPROJECT CAN FOLLOE MY GIT LINK :  https://github.com/naimul3070/Install-OpenProject-Project-Managmen-Software-local-servert.git

# 2.Install PG-ADMIN

## FOR INSTALL PG-ADMIN CAN FOLLOE MY GIT LINK :    https://github.com/naimul3070/Install-PG-Admin.git

### AFTER INSTALL GET THE SERVER INFORMATION FROM : 

cd/etc/openproject/config


## After Keep the inforUninstall openproject and related all file and directory

# Mostly FOM etc Directory and bin DIrectory

dpkg --list
sudo rm -rf OpenProject
sudo apt autoremove -y
sudo apt autoclean
sudo apt cleansudo apt purge --auto-remove gimp
sudo apt --purge remove gimp


## After That re-install OpenPrject

FOR INSTSLL OPENPROJECT CAN FOLLOE MY GIT LINK :  https://github.com/naimul3070/Install-OpenProject-Project-Managmen-Software-local-servert.git

## Create A New Databased in the OpenProject Existing POSTGRESSQl server and restore the backup database to new db including postgress root db
# Start configuring OpenProject

sudo openproject configure

## Configure PostgreSQL
<img width="251" alt="image" src="https://user-images.githubusercontent.com/50922314/159857342-f87d6ca2-0348-49cf-9520-f1c6af0f38f8.png">

## Configure PostgreSQL
Select Existing PostgreSQL server and database the new created db and existing id pass

<img width="299" alt="image" src="https://user-images.githubusercontent.com/50922314/159857800-60626289-f4bb-478b-8876-84af71c5b0d5.png">

Rest of All Process is same 


# Domain: Use The New OpenProject TCP/IP

<img width="310" alt="image" src="https://user-images.githubusercontent.com/50922314/159858431-64e7e4cc-7197-43c1-b423-402901d7d667.png">

# Skip SSL
# Install subversion repository support
# skip STMP
