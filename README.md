# Secret Recovery Methods

This repo contains resources and links related to secret/key recovery. There are two broad approaches to recovery of a secred, (1) methods that reconstruct the key or (2) methods that force a rekey of the Identifier. Both require the existense of some sort of super-user that can validate the request and initiate the recovery eith by (1) sending the old key to the wallet, or (2) issuing a key roll-over event to the users chosen ledger.

## Resources

- [DIF blog post about cryptographic secret recovery](https://medium.com/decentralized-identity/dif-id-wg-starting-work-on-cryptographic-secret-recovery-204117b6a2ab) (May 2020)
- [Section 5.5 in this OpenID "OpenID Self Issued Identifiers" draft](https://bitbucket.org/openid/connect/src/master/SIOP/draft-jones-self_issued_identifier.md)

## Methods for Recovery of the old key

- [Fuzzy Encryption](https://github.com/decentralized-identity/fuzzy-encryption)
- [Horcrux Protocol](https://github.com/decentralized-identity/horcrux)
- [SeedQuest](https://github.com/reputage/seedQuest)

## Methods for Rekeying the Identifier

## Additional Links

- [The Thoughful Biometrics Workshop](https://thoughtfulbiometrics.org/) (February 2021)

