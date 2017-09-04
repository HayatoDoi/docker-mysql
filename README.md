### docker-mysql
Docker Compose for ```Mysql, PhpMyAdmin```  

#### Overview
```
./
├── LICENSE
├── README.md (this file)
├── docker-compose.yml
└── volume (mysql volume)
```


#### Demo
MySql starts up in port 3306.  
PhpMyAdmin starts up in port 8080.  

#### Requirement
- Docker version 17.07.0-ce
- docker-compose version 1.15.0

#### Usage
localhost:3306 MySql  
[http://localhost:8080](http://localhost:8080) PhpMyAdmin  

#### Install
- Clone this repository
`git clone https://github.com/HayatoDoi/docker-mysql.git`
- Move to docker-mysql
`cd docker-mysql`
- Start
`docker-compose up`
- Stop
`docker-compose stop`
- Remove
`docker-compose rm`

#### Default Mysql Password
- user : root
- password : root

If you want to change password, edit docker-compose.yml  

#### Licence
These codes are licensed under CC0.  
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)  

#### Author
[HayatoDoi](https://github.com/HayatoDoi)  
