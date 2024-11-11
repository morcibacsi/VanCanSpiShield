# VAN CAN SPI Shield

### What is it ?
This is an SPI "shield" designed for my [PSA VAN-CAN protocol bridge hardware][psavancanbridgehw].

On one side, it has an MCP2515 CAN bus controller, and on the other side, it has a TSS463C VAN bus controller. Both sides contain all the necessary components. Obviously only one side can be used at a time. 

The files are created with KiCad. 

The main branch contains only this readme file as there might be multiple revisions and having a continuous history does not really make sense. 
So every revision will have its own branch. They will be in the state as I sent them to the manufacturing company.

### Available revisions

- [Rev 1.0][version_10]

[psavancanbridgehw]: https://github.com/morcibacsi/PSAVanCanBridgeHW
[version_10]: https://github.com/morcibacsi/VanCanSpiShield/tree/v1.0