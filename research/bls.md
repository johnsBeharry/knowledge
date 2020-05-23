# BLS — [Boneh-Lynn-Sacham](https://en.wikipedia.org/wiki/Boneh–Lynn–Shacham) Signature Scheme



### Aggregatable

It’s possible to aggregate all types of primitives (secret keys, public keys, signatures) and the result is always another valid primitive. If you aggregate two secret keys, the result is a new valid secret key. If you aggregate the two corresponding public keys of the secret keys, the result is a new public key that matches the previously aggregated secret key’s public key. If you aggregate two signatures that were created with the two previously aggregated secret keys and the same message hash, the new signature would also validate against the aggregated public key. Primitives which were already aggregated can also be further aggregated, independent from the order in which it happens.

- https://blog.dash.org/secret-sharing-and-threshold-signatures-with-bls-954d1587b5f

