# Stagg EKG Pro Home Assistant Integration
 Home Assistant Integration for contolling a Fellow Stagg EKG Pro Electric Kettle over WiFi

 I was inspired By [Levi's Stagg EKG+ integration](https://github.com/levi/stagg-ekg-plus-ha) which sadly does not work for my [Stagg EKG Pro](https://fellowproducts.com/products/stagg-ekg-electric-pour-over-kettle). While others had some success getting the [EKG Pro working over bluetooth](https://community.home-assistant.io/t/ble-reverse-engineering-a-fellow-stagg-ekg-pro-kettle/863026), it exposes an unsecured HTTP endpoint at {Kettle_IP}/cmd from which a number of very useful commands can be run remotely. This repository is a WIP attempt to integrate the kettle with Home Assistant over WiFi, using this interface.
