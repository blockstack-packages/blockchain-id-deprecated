# Blockchain ID

[![Slack](http://slack.blockstack.org/badge.svg)](http://slack.blockstack.org/)

[![Read the Wiki](/images/read-the-wiki.png)](https://github.com/blockstack/blockchain-id/wiki)

A blockchain ID is a unique identifier that is secured by a [blockchain](https://en.wikipedia.org/wiki/Block_chain_(database)). Blockchain IDs are simultaneously secure, human-meaningful, and decentralized, thereby overcoming [Zooko's triangle](https://en.wikipedia.org/wiki/Zooko%27s_triangle). Users can cryptographically link their blockchain IDs to a profile containing arbitrary information (e.g. name, biography, website link, public key, and social graph), by associating a hash of the profile with the ID registered on the blockchain. Blockchain IDs work with [Blockchain Auth](https://github.com/blockstack/blockchain-id/wiki/Blockchain-Auth) to eliminate passwords and third parties from the user authentication flow of websites and applications, creating a decentralized Single Sign-On (SSO) system.

### Getting Started

Several tools are needed to register, resolve, view, and authenticate blockchain IDs:  

- [Blockstore](https://github.com/blockstack/blockstore), which is used for registering blockchain IDs on the Bitcoin blockchain. Blockstore has an external storage system built-in for storing profile data off-chain.  
- [Blockstore-client](https://github.com/blockstack/blockstore-client), which provides an interface for creating and managing blockchain IDs, blockchain ID namespaces, and storage records associated with them.  
- [Blockchain-auth-js](https://github.com/blockstack/blockchain-auth-js) or [blockchain-auth-python](https://github.com/blockstack/blockchain-auth-python), libraries that support generating, decoding and verifying auth request and auth response tokens.  

Optional software that can be used for building blockchain ID services includes:  

- [Resolver](https://github.com/blockstack/resolver), a scalable server for resolving username-to-profile-data mappings.  
- [Registrar](https://github.com/blockstack/registrar), software for registering and updating blockchain IDs.  
- [DHT mirror](https://github.com/blockstack/dht-mirror), software that improves read/write performance for the Blockstore DHT.  
- [Indexer](https://github.com/blockstack/indexer), for information on names registered on the blockchain, the associated data, blockchain transactions etc. JSON interface for calls to a processed index (stored in a database).  
- [Virtual chain](https://github.com/blockstack/virtualchain), a Python library for creating virtual blockchains on top of a well-known cryptocurrency.  

### Use Cases

- Secure communications applications  
- User authentication for apps and websites  
- Human-readable cryptocurrency addresses  
- Infrastructure for the Internet of Things  
- Streamline KYC/AML compliance  
- Alternative to the Domain Name System  
- Alternative to Certificate Authorities  
- Alternative to insecure identifiers e.g. Social Security Numbers  

### More Information

More information about blockchain IDs, including the latest software, formats, and schema, can be found in the Blockchain ID Wiki.

[![Read the Wiki](/images/read-the-wiki.png)](https://github.com/blockstack/blockchain-id/wiki)
