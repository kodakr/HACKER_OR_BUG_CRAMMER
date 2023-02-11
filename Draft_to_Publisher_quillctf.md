## Values/ Impact of Challenge
 - Challenge assumes a real-life hacking scenerio hence involving some OSINT.
 - Demands u see what code does not what a dev says it does. Hence arbitrary variable names.
 - Ability to deal with customized/personal code not just DEFI, ERC et al.
 - Demands indepth understanding of EVM storage layout.
 - Hacker deals with code. code is code irrespective whats coded.
 
## Hint/Info to participant
- Link to [Moloch's tweet](https://twitter.com/Kodak_Rome/status/1624372583310262279?t=_iNw3oWhcMmISeECaDBTTA&s=19) (Preimage found in updated source code).
- Moloch is the 3rd Person of cabals.
- Failure to provide deep detail of steps taken is regarded as failure (cause it was deployed)

## Expectation from participant
- Focus and not distracted by scattered code, arbitrary varible terms.
- Understand & dissasemble contract storage & get Moloch-encrypted passss using ethers.js
- Decrypt the retrieved value using [Moloch-Algorithm](https://twitter.com/Kodak_Rome/status/1624372583310262279?t=_iNw3oWhcMmISeECaDBTTA&s=19)
- Pass the decrypted value into uhER778() while solving some challenges as well. Setting  `realHacker[msg.sender] = true`
- Withdrawing 1 wei via sendGrant()
- **Challenge Passed**
## Details required in participants POC
- Detailed formula for finding slot of dynamic struct
- state the derived string
- Details of decrypting Moloch-algorithm
- state decrypted preimage
- Expliain bypass `keccak256(abi.encodepacked()`.
- Stated Attacker address expected to reflect true from `mapping(address => bool) public realHacker;`

## Personal Appeal/request
1. Being aware of the current situation in which challenge contracts are nolonger deployed to goerli due to some potential malpractice.
I'll like to request that this be revoked for this challenge due to the following reasons:

- The challenge is heavily based on extracting data 4rm storage. Hence should be deployed
- If deployed, *Unity* of solution/extracted answer/string value is achieved. Hence scoring made easy.
- The nature of this challenge isnt revealing via transaction scan as most of its functions are not even required to hack the contract, also doesnt require `selfdestruct()` which can be seen on etherscan. (If theres a way im not aware of pls notify me via discord).
- Infact even if a whole attacker contract can be seen via etherscan, participant still has to provide details of: algorithm decryption, formula for extracting data in `struct`, `keccak256(abi.encodepacked()` manipulations.

## Constructor input for deployment
`{
molochPass: "BLOODY PHARMACIST",
_B: ["WHO DO YOU", "SERVE?"],
A: ["0x5B38Da6a701c568545dCfcB03FcB875f56beddC4","0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2","0x4B20993Bc481177ec7E8f571ceCaE8A9e22C02db"]
_PASSSS: ["KCLEQ","BGTGJQNGP","ZJQQBW*NFCPKCAKQR"]
}`

## Expected answer (using above inputs)
