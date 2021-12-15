# metaRoot

# Paper for the Protocol

Right now the entire internet https() security is in hands of just few and if the single party fails the entire network security fails.  metaRoot  will address the root cause of this problem, we discuss how we can code a VM over Avalanche subnet that  proves the unique names and as well work as a decentralized certificate authority to issue certificates. Implementing a protocol over the avalanche subnet where the construction is such that namespaces resolves to certificates that are compact and are easily verifiable by billions of devices around the globe.

Using the sub layer that is granted by subnet to achieve sync coordination of the certificates and namespaces. 

The initial members would be rewarded to integrate ANS protocol on the native AVAX token.


**Introduction**

Short names on the internet largely rely on the single trusted authority for the consensus , otherwise its meaningless and not secure. The trilemma of the zooko triangle takes form. A working subnet VM can fix this , [HandShake Ref] A committed sparse Merkelised proof ([link](https://github.com/bcoin-org/bcrypto/blob/master/lib/mrkl.js)) that contains the top level domain names with certificates pinned to them, this requires a re-design in trust anchor around the POS blockchain. Using the underlying subnet proof of stake consensus we would be allocating the resources to open source communities and individual members from different part of the world. 

**Working this out**

The trusted model where tld and certificates are entrusted under a custodial model as we pointed out above and has been pointed again in the [handshake protocol](https://hsd-dev.org/files/handshake.txt) ,handshake solves this problem is via canonically  indexing data to the blockchain, handshake admits in the paper that without a native token its not easy to sybil the network but that does not really solve issues like if one controls majority stake or validates most amount of blocks within the network. Handshake currently uses POW model that seems to be inherently slow as number of transaction will grow. 


**Proof of Stake**

Owners staking proofs and submitting to the network (How?)


Proving true ownership with staking could reduce the risk where the honest name space owner must submit minimum amount of native tokens every time they make a claim over a TLD with CA associated. To reduce the spam over the network the resource transfer will happen over the period of time once the proofs of the ownership correctly resolves over chain. 

Solution 1 Using Avalanche consensus for light weight client by providing Merkelised hashes for the proof of namespaces with CA

Implementing a metaUTXO model where on chain ordering can be done with POS style block management that allows bitcoin style implementation for script parsing

**Naming History**

ENS, HandShake
