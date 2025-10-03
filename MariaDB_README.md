# MariaDB Commands

# About Me

> [!IMPORTANT]
> Er. Amit Joshi :)  
>  [Repo Link](https://github.com/amitjoc/commands)  

# MariaDB Installation

## On Ubuntu OS 

 ### Before Installation 

> [!NOTE]
> First Update package information and upgrade
> ```
> sudo apt update
> sudo apt upgrade
> ```

 ### Search Package

To Search `MariaDB Server` package on `apt repository`

```
sudo apt search mariadb-server
```

### Install Package 

To Install `Mariadb Server and Client` 
```
sudo apt install mariadb-server mariadb-client
```

### Secure Installation Command

> [!NOTE]
> Then Must run Secure Installation command 
>
> ```
> sudo mariadb-secure-installation
> ```

### Manage MariaDB Service 

#### Start Service

To start MariaDB Server service 
```
sudo systemctl start mariadb
```

#### Check Status of Service
To Check status of MariaDB Server service 
```
sudo systemctl status mariadb
```

#### Enable Service on Boot

Enable MariaDB to start on boot
```
sudo systemctl enable mariadb
```

#### Verify/Connect MariaDB Service 
Verify or connect Maraidb after installation 
``` 
mariadb -u root -p
```














