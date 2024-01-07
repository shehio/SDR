# SDR
[Software-Defined Radio](https://en.wikipedia.org/wiki/Software-defined_radio)

## Electromagnetic Spectrum
![image](https://github.com/shehio/SDR/assets/4094464/d0c16fe7-4715-4467-8d09-47189fbae50c)
Source: [Wikimedia](https://en.wikipedia.org/wiki/Electromagnetic_spectrum).

## Applications

### Metro Systems
| Location | Card Name | Protocol |
|---|---|---|
| Boston | Charlie | MIFARE DESFire EV1 |
| London | Oyster | MIFARE Classic / MIFARE DESFire EV1 |
| NYC | OMNY | Contactless EMV |
| Paris | Navigo Easy | [Calypso](https://en.wikipedia.org/wiki/Calypso_(electronic_ticketing_system)) |
| Seattle | Orca | MIFARE DESFire EV1 |


## Standards
### Radion Frequency ID (RFID)
RFID cards have a microchip and an antenna to communicate with the readers. They follow different protocols that allow or do not allow encryption and handshake.

#### Standard Proximity Cards [125 KHz]
Outdated cards that don't have any encryption.

#### Contactless Smart Cards [13.56 MHz]
Like [MIFARE](https://en.wikipedia.org/wiki/MIFARE) DESFire EV1 and EV2, which use AES 128 encryption, and NFC (Near Field Communication), they're more secure but have a smaller read distance.


---
### How Does MIFARE DESFire EV1 Work?
1. The reader initiates the conversation by creating an RF field, which powers the card's chip and allows data transmission.
2. Mutual Three-Pass Authentication using a security handshake.
3. Application-level authentication.
4. File Access and Operations include reading data, writing data, incrementing or decrementing values, and creating or deleting files.
