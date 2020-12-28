```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512

```
Document version: **2016.09.27** ([history](#document-history))

# PGP Key

My PGP public key fingerprint is
[`0342 C809 99FB 1A06 FD0F 9533 8392 C992 D925 00A9`][pubkey].

[The source of this document][self] is signed with that key. Please verify that
the signature is still valid. Verification of the current version of this
document can be performed using [GnuPG][gnupg]:

```sh
gpg --recv-keys 0x0342C80999FB1A06FD0F95338392C992D92500A9
wget -O- https://github.com/smkent/pgp/raw/master/README.md | gpg --verify
```

To verify a [prior version][commits], replace `master` in the above URL with the
[git commit ref][gitref] corresponding to the version you would like to verify.

# Key signing policy

I am willing to sign PGP keys when provided with sufficient proof of identity
and private key ownership.

I use the PGP key signature levels are as follows:

* I do not create new **level 0** signatures ("I will not answer"). Existing
  level 0 signatures predate the existence of this document and indicate that
  the key owner is well known to me.
* I do not create **level 1** signatures ("I have not checked at all").
* I create signatures at **level 2** ("I have done casual checking") and **level
  3** ("I have done very careful checking").

See below for how to request a signature. If you request that I sign your key,
please be willing to sign my key as well.

## I have done very careful checking (Level 3 signature)

* I am willing to sign your key if you are personally well known to me.
* I am willing to sign your key if we exchange full PGP key fingerprints and
  government-issued photo IDs, either in person or via end-to-end encrypted
  video conference. Acceptable photo IDs are one of a United States passport,
  state driver license, or state ID card.

To request a level 3 signature, contact me at the e-mail address in my [public
key][pubkey].

## I have done casual checking (Level 2 signature)

I am willing to sign your key if you provide me with a color scan that includes
the following:

* A government-issued photo ID (United States passport, state driver license,
  or state ID card). Only your name and the photo are needed to verify your
  identity, so you may conceal or remove additional personal information if you
  prefer.
* A handwritten copy of both your full public key fingerprint and e-mail
  address.

To request a level 2 signature, send a signed and encrypted e-mail containing
the above information to the e-mail address in my [public key][pubkey].

## Signature creation and delivery

After meeting the above identity verification requirements, I will individually
sign each of the UID(s) corresponding to your identity and e-mail an encrypted
copy of your public key for each signed UID to its corresponding e-mail
address. You must decrypt the signed key(s), which provides sufficient proof
that you control the corresponding private key.

PGP key signatures I create do not expire.

I reserve the right to not sign a particular key or UID at my own discretion.

## References

* My key signing policy is partially inspired by [Aaron Toponce's PGP key
  signing policy][aarontoponce].

# Document history

This document may be revised at any time. Material changes to my key and/or
signing policy are listed here. For all document changes, please see [the
repository's commit history][commits].

* **2016.09.27**: Initial document published

[aarontoponce]: https://pthree.org/my-pgp-key-signing-policy/
[commits]: https://github.com/smkent/pgp/commits/master
[gitref]: https://git-scm.com/book/en/v2/Git-Internals-Git-References
[gnupg]: https://www.gnupg.org/
[pubkey]: https://keys.openpgp.org/search?q=0x0342C80999FB1A06FD0F95338392C992D92500A9
[self]: /README.md
```
-----BEGIN PGP SIGNATURE-----

iQIzBAEBCgAdFiEELzwhe+BXPUKPZyKW62lgIps+KmsFAl/qVw0ACgkQ62lgIps+
KmtIQg/+Lw3/kxOJaqFyYY+y3ahDvXSHcO2aSLktpnBmNNNRsaZKFh+vPBIMoVLL
QUN24q7OrB3x3+oablKmd1WT5vKIuM4FLOUmkT0ZZ5O4P5ZuLjInYA1/0JtSc4R4
jsCOjaNEYtJSU1IY+0yEoeJMQgZXi04ctDFAofW0kUpQOgO5ULhqgCCY0CmxI/lj
k/WQqqe83K7jGQM7kKlTDMXCxkQyYyLipwnTsWODdPrkV1lWCMVVhvvNuRFBiDCr
l6bAYIYHleKEzKKN6Woown3Kb+PzHbGbPZKmgQ2xAzOw+uxxSdTe/vzbi10Ge9l9
U8Jl/nQwKjsIAyC2PDI6Qm8A39xPzPtURxknK1v8KrBZnnLdIVdH5Xu+yW2J/UyW
x7Yx2KvWO6bUdEkcfsfa9T6Mg2jZcBeVL4Y4n8rBfTw1tZy9BvSnYxZGXPY0NvyV
A5em1bd7Mhie1m9wz1Ir0RrKjxWp19GQSeOouHEPIgWKVtsyI5o6f2qwnGkEAY0m
q/5QrUrjsJ/jkRSPZVUFov3+VU/d8+3wWHOx4V5eOaXNeNzqg5ocdxwKHH4XJXx/
Scaozr9qhZzpzM30A02NJXjdN9LkR/XWd7L5sFo+Nh9HeV0+OsWVCx4OYjimx0q/
s7mfDjRDNt+6kvAXhEYT+QDYOxoAcwOaljS/bKDhQjMu/9XTuFY=
=lFqU
-----END PGP SIGNATURE-----
```
