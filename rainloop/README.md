## wonderfall/rainloop

![](https://i.goopics.net/nI.png)

#### What is this?
Rainloop is a simple, modern & fast web-based client. More info on the [official website](http://www.rainloop.net/).

#### Features
- Based on Alpine Linux Edge
- Latest Rainloop **Community Edition**
- Contacts (DB) : sqlite, or mysql (server not built-in)
- nginx + PHP7
- OPCache (opcocde), APCu (local) installed and configured.

#### Build-time variables
- **GPG_rainloop** : fingerprint of signing key

#### Environment variables
- **GID** : rainloop group id *(default : 991)*
- **UID** : rainloop user id *(default : 991)*
- **UPLOAD_MAX_SIZE** : maximum upload size *(default : 10G)*
- **APC_SHM_SIZE** : apc memory size *(default : 128M)*
- **OPCACHE_MEM_SIZE** : opcache memory size in megabytes *(default : 128)*

#### Volumes
- **/rainloop/data** : data files.

#### Ports
- **8888***

#### Reverse proxy
https://github.com/Wonderfall/dockerfiles/tree/master/reverse
https://github.com/hardware/mailserver/wiki/Reverse-proxy-configuration
