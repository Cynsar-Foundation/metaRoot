# metaRoot

Metaroot is an experimental naming service that lets  anyone, anywhere in the world to register names and associate identity. Metaroot uses peer-to-peer technology to operate with no central authority: managing transactions and issuing names are carried out collectively by the network. Metaroot Core is the name of open source software which enables the use of this service.

# Finding

Right now the entire internet https() security is in hands of just few and if the single party fails the entire network security fails along with the naming service that powers domains like www.zyz.com, users must agree on their control across trust boundaries.  metaRoot will address the root cause of this problem, we discuss how we can implement a custom protocol that proves the unique names and as well work as a decentralized certificate authority to issue certificates and unique name spaces. Implementing a protocol of which the construction is such that namespaces resolves to certificates that are compact and are easily verifiable by billions of devices around the globe.

Humans are incapable of securely storing high-quality cryptographic keys, and they have unacceptable speed and accuracy when performing cryptographic operations. (They are also large, expensive to maintain, difficult to manage, and they pollute the environment. It is astonishing that these devices continue to be manufactured and deployed. But they are sufficiently pervasive that we must design out protocols around their limitations. ([link](https://web.archive.org/web/20011020191610/http://zooko.com/distnames.html))

Nick Szabo disagrees the trilemma ([link](https://nakamotoinstitute.org/secure-property-titles/)) and provides cryptographic solutions with a simple replicated database that can verify the transfer using  `2f+1` threshold, with a voting to remove malice users and adding honest users. Hence a democratic system that has a math based quorum to achieve resilience against malicious users. The author points out that with secure timestamps, initial bootstrapping takes place with first-come rather than emergent respect basis.

# What is DNS?


**Introduction**

Short names on the internet largely rely on the single trusted authority for the consensus , otherwise its meaningless and not secure. The trilemma of the zooko triangle takes form. A working decentralised system that stores names and certificate can fix this , [HandShake Ref] A committed sparse Merkelised proof ([link](https://github.com/bcoin-org/bcrypto/blob/master/lib/mrkl.js)) that contains the top level domain names with certificates pinned to them, this requires a re-design in trust anchor around the POS blockchain. Using the underlying subnet proof of stake consensus we would be allocating the resources to open source communities and individual members from different part of the world. 

**Working this out**

The trusted model where tld and certificates are entrusted under a custodial model as we pointed out above and has been pointed again in the [handshake protocol](https://hsd-dev.org/files/handshake.txt) ,handshake solves this problem is via canonically  indexing data to the blockchain, handshake admits in the paper that without a native token its not easy to sybil the network but that does not really solve issues like if one controls majority stake or validates most amount of blocks within the network. Handshake currently uses POW model that seems to be inherently slow as number of transaction will grow. 


**Proof of Stake**

Owners staking proofs and submitting to the network (How?)

Proving true ownership with staking could reduce the risk where the honest name space owner must submit minimum amount of native tokens every time they make a claim over a TLD with CA associated. To reduce the spam over the network the resource transfer will happen over the period of time once the proofs of the ownership correctly resolves over chain. 


**Naming History**

ENS, HandShake
