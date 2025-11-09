# CBOR Ordinal Type Compression (OTC) for Value Groups & Map Keys

This is the working area for the IETF Internet-Draft, "CBOR Ordinal Type Compression (OTC) for Value Groups & Map Keys".

## Abstract

This document standardizes a method to compress groupings of CBOR ordinal types such as integers and floats. The concept is then applied to the specific case of using integers as keys in CBOR maps that can be used by protocol specifications to enable re-use of the most concise CBOR encodings. Such compression to enable these encodings are desirable in highly constrained environments.

## Building the Draft

Formatted text, XML and HTML versions of the draft can be built using `make`.

```sh
$ make
```

This requires that you have the necessary software installed. See [the instructions](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md).

## Contributing

See the [guidelines for contributions](https://github.com/ietf-wg-drip/draft-ietf-drip-auth/blob/master/CONTRIBUTING.md).