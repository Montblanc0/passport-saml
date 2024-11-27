# Passport-SAML (fork)

This is a fork of the [original](https://github.com/node-saml/passport-saml) SAML 2.0 authentication provider for
[Passport](http://passportjs.org/), the Node.js authentication library.

## Purpose

Replaces @node-saml/node-saml dependency with [@montblanc0/node-saml](https://github.com/montblanc0/node-saml) to enable an additional strategy option:

- `allowUnsignedEncryptedAssertions`: when `true`, bypasses signature validation when a SAMLAssertion is both encrypted and unsigned (defaults to `false`)

## Installation

```shell
npm install @montblanc0/passport-saml
```

For more instructions, please refer to the [official README](https://github.com/node-saml/passport-saml/blob/master/README.md).