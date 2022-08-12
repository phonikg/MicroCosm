# MicroCosm
MicroCosm: A Permissionless Chain for the InterBlockchain of Things


John Gerryts

@PhonikG

https://github.com/phonikg/MicroCosm




Abstract: Experimental research focused on a protocol that will allows for p2p or m2m transactions between low cost resource constrained devices.






Protocol: Tendermint based and Cosmos-SDK compatible. Goal will be to customize those components necessary to allow for a successful light client deployment on MIPS or smaller CPU, MCU, or other Controllers. 

Network: Communication should be viable across LTE-M or NB IoT channels. Goal will be to customize messaging to not exceed bandwidth and throughput limitations for these industry standard IoT Networks.

Client: Light Client or Wallet shall need to be designed in such a way that it will consume minimal resources(storage, processing, and memory) to allow for deployment on a target device. 

Target Device: A general example of target device would be any common, low cost, resource constrained device. Preferably this device will be paired with a secure element. A more specific example would be an ESP32Secure(See link below).

https://blog.ebv.com/espressif-esp32-wi-fi-module-with-microchip-atecc608a-secure-element/


