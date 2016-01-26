# RackHD/OpenStack Coordinator (shovel)

You can install Shovel by cloning this repo

```sh
git clone https://github.com/openstack/shovel.git
sudo mv Shovel /var/
cd /var/Shovel
sudo npm install
sudo ./scripts/post-install.sh
sudo npm start
```
Or you can use npm install to Download shovel package

```sh
npm install node-shovel
sudo mv node_modules/node-shovel /var/Shovel
cd /var/Shovel
sudo ./scripts/post-install.sh
sudo npm start
```

Once the service is running, you can use swagger GUI to setup RackHD, Ironic, Keystone and Glance hostname and login information: http://<Shovel-IP>:9005/docs (You can also change Shovel Port(default:9005) note that the service will restart with the new configuration. 

## Shovel-Ironic Set info Example:

![alt text](snapshot/ironic_info.png)

## Shovel Set Port Example:

![alt text](snapshot/shovel_settings.png)

