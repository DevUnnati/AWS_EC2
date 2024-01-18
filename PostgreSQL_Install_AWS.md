# Install PostgreSQL on AWS EC2 Instance

<b> Step1: </b> Update the system

sudo apt update

<b> Step2: </b> Install PostgreSQL Server

sudo apt install postgresql postgresql-contrib

<b> Step3: </b> Start MySQL Services

sudo service postgresql start

<b> Step3: </b> Verify install successfully by getting Version

psql --version

