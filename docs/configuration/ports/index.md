#  Communication Ports

Almost every single one of our own software has to exschange data between itself and either other devices or services. This usually happens through communication ports. These ports abstract away the underlying technology (serial, network, ...).

## Layers

A layer defines the type of communication to be used. Options are Serial, TCP Server, TCP Client, UDP Sender and UDP Receiver.

### Serial