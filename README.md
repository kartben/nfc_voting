nfc_voting
==========

### Dependencies

For the galileo you need to use a linux distibution.
* Python
* Python-nfcpy
* Mosquitto

On the server side you will need.
* Python
* Python-nfcpy
* Python-pygame
* Mosquitto
* NodeJS
* MongoDB


### Usage
First you must launch the mqtt broker and the three readers on the galileo, one for each nfc reader with a different vote value.
```
mqtt-broker ************TODO*************
python read.py 002:004 0
```

On the server side you have to run the mongoDB database and the mqtt broker.
```
************TODO*************
```
Then you run the NodeJS server and the display python programm.
```
************TODO*************
```
