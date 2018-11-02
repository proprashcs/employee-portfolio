

# User-Client
Portfolio application build in Nodejs using Mysql :

If need any help regarding Node JS programming feel free to contact me on
prashantcs0061@gmail.com




## Install Dependencies

```shell
npm install
```
## Create Database 'portfolio' and table projects

```shell
CREATE TABLE `projects` (
  `id` int(11) NOT NULL,
  `title` varchar(255) NOT NULL,
  `description` text NOT NULL,
  `client` varchar(255) NOT NULL,
  `service` varchar(255) NOT NULL,
  `url` varchar(255) NOT NULL,
  `image` varchar(255) NOT NULL,
  `date` date NOT NULL,
  `create_date` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

## Run Application

```shell
node app
```

Thats All.
