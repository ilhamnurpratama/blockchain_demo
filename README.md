# Blockchain_Demo
This repository is used for developing smartcontract for the telkomsel roaming private blockchain.

|Date|File|Version|Updates|
|----|----|-------|-------|
|2023-07-25|smartcontract.go|0.1.0|Initial version merge with smartcontract_original.go|
|2023-07-25|smartcontract_original.go|0.1.0|Original smart contract from Hyperledger|
|2023-07-25|smartcontract_v1.go|0.1.0|Initial version|
|2023-08-14|logic.js|0.1.0|Blockchain logic for transactions|
|2023-08-14|model.cto|0.1.0|hyperledger model for tsel roaming|

## How to Blockchain

## How to Start Blockchain
1. Change directory to fabric-dev-servers
  cd fabric-dev-servers
2. Exporting fabric versions
  export FABRIC_VERSION=hlfv12
3. Start fabric
   ./startFabric.sh
4. Create admin card
  ./createPeerAdminCard.sh
5. Start composer
  composer-playground 
