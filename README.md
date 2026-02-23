Status: libolm was [officially deprecated](https://gitlab.matrix.org/matrix-org/olm/-/commit/6d4b5b07887821a95b144091c8497d09d377f985) on 2024-07-31. This repository is now kept for archival purposes only.

***

# olm

Olm (libolm) is an independent Apache-licensed implementation of the Double Ratchet cryptographic ratchet in C & C++, also including the new Megolm group ratchet as used in Matrix.

The Olm repository now lives at https://gitlab.matrix.org/matrix-org/olm.

We don't host Olm on Github as that would constitute re-exporting its cryptography to/from the US, which technically requires us to file additional paperwork with the US government: see https://www.bis.doc.gov/index.php/policy-guidance/encryption/6-faqs for details.  Given Olm is currently developed in the UK & France, and https://matrix.org/git is hosted in UK / Holland / Germany, we store the code on this side of the Atlantic :)

## Security issues

If you think you found a security issue in libolm, any of its bindings or the Olm/Megolm protocols, please follow our [Security Disclosure Policy](https://matrix.org/security-disclosure-policy/) to report.
