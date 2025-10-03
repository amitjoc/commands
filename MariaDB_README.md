# MariaDB Commands

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

To start MariaDB Server service 
```
sudo systemctl start mariadb
```

To Check status of MariaDB Server service 
```
sudo systemctl status mariadb
```

Enable MariaDB to start on boot
```
sudo systemctl enable mariadb
```

Verify or connect Maraidb after installation 
``` 
mariadb -u root -p
```
