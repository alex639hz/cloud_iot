# cloud_iot
configurable automation system based on an integrated system of embedded devices (RespberryPi and 8051) with a cloud system of API server and DB.
# Embedded system responsibilities are (server(s) and embedded i/o boards 8051)
(*) collect data and transfer it to the cloud
(*) manage connected devices (a group of 8051 devices connected over RS485)
# cloud API server responsibilities (main server)
(*) collect data by API request and store it in DB
(*) provide the interface to stored data
(
