#### Node Discovery

1. Each node has a direcotry of other nodes they have connected to
2. A last seen timestamp is kept with each address in the dictionary
3. A randomised subset of this directory is passed on to other nodes when they make a `getaddr` request.

[1a]: https://en.bitcoin.it/wiki/Satoshi_Client_Node_Discovery#Handling_Message_.22getaddr.22	"getaddr"

