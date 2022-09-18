# MicroCosm
MicroCosm: For the InterBlockchain of Things

John Gerryts | @PhonikG


Abstract: An ideation for experimental research focused on m2m transactions between low cost and resource constrained devices connected within or across the Cosmos Ecosystem, i.e. - The Interchain.




Problem: There are a few key issues when trying to deploy a blockchain client on an IoT type device:

The majority of layer 1 protocols target "resource maximized" general purpose computers(laptop/desktop/server) and are not necessarily able to run on resource constrained devices and the IoT tailored communication networks they communicate across. 

The majority of Layer 1's do not support popular, or off-the-shelf, ECDSA curves and therefore require customized hardware to support hardware secured keys/wallets.

Solution: Analyze, identify, and prioritize all components of the Cosmos stack that are required and can be applied and/or optimized for popular resource constrained devices. For example:

Testing Cosmos-SDK light clients to determine the minimum class of target device that has ample resources to deploy a minimum viable application.
Deploying wallets based on NIST P-256 curve supported in v0.45 of Cosmos-SDK.

Target Device: A general example of target device would be any common, low cost, resource constrained microprocessor. Preferably this device will be paired with a secure element. More specific examples for the purposes of this project would be an ESP32-S3 paired with an Infineon Trust M Secure Element that supports NIST P256. (see links below)

Target Protocol: Tendermint based and Cosmos-SDK compatible. The goal of MicroCosm is to determine if current applications allow for a successful wallet or light client deployment on an MCU.

Target Network: Communication needs to be viable across LTE-M or NB IoT communication channels. Goal will be to successfully communicate within throughput limitations for these industry standard IoT Networks.

Target Demographic: MicroCosm would allow for everyone, Maker or IoT Industry leaders, to kick-start development of any IoT project requiring m2m payments and signed messaging.
Project Goals:  The following is a prioritized list of goals of MicroCosm:

Immediate Goals (WITHIN the scope of this application)
Attempt to deploy a functional wallet on a target device.
Integrate a Secure Element to securely create keys, store keys, and sign transactions with the above mentioned wallet.
Attempt to deploy a more full featured light client on a target device.
Long Term Goals (NOT within the scope of this application)
Develop an on-board web portal to easily deploy and manage a target device locally 
Develop an Administrative Web Portal in order to deploy and manage many target devices, including secure OTA firmware upgrades.



Resource Links:

https://www.adafruit.com/product/5483

https://www.adafruit.com/product/4351


