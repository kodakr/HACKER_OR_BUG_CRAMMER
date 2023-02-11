## Values/ Impact of Challenge
 - Challenge assumes a real-life hacking scenerio hence involving some OSINT.
 - Demands u see what code does not what a dev says it does. Hence arbitrary variable names.
 - Ability to deal with customized/personal code not just DEFI, ERC et al.
 - Demands indepth understanding of EVM storage layout.
 - Hacker deals with code. code is code irrespective whats coded.
 
## Hint/Info to participant
- Link to [Moloch's tweet](https://twitter.com/Kodak_Rome/status/1624372583310262279?t=_iNw3oWhcMmISeECaDBTTA&s=19) (Preimage found in updated source code).
- Moloch is the 3rd Person of cabals.

## Expectation from participant
- Focus and not distracted by scattered code, arbitrary varible terms.
- Understand & dissasemble contract storage & get Moloch-encrypted passss using ethers.js
- Decrypt the retrieved value using [Moloch-Algorithm](https://twitter.com/Kodak_Rome/status/1624372583310262279?t=_iNw3oWhcMmISeECaDBTTA&s=19)
- Pass the decrypted value into uhER778() while solving some challenges as well. Setting  `realHacker[msg.sender] = true`
- Withdrawing 1 wei via sendGrant()
- **Challenge Passed**

## Personal Appeal/request
Being aware of the current situation in which challenge contracts are nolonger deployed to goerli due to some potential malpractice.
I'll like to request that this be revoked for this challenge due to the following reasons:
- // details demdnded
- The challenge is heavily based on extracting data 4rm storage. Hence should be deployed
- One solution/ extracted answer/ string value expected. Hence scoring made easy.
- The nature of this challenge isnt revealing via transaction scan as most of its functions are not even required to hack the contract, also doesnt require 'selfdestruct' which can be seen
