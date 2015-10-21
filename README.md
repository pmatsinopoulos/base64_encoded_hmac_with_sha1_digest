# base64_encoded_hmac_with_sha1_digest
Demonstrates how one can base64 encode an HMAC (with SHA1 algorithm) digest - Swift

It is a Swift application example, that takes a payload and a secret key and creates a Base64 encoded version of an 
HMAC digest (algorithm SHA1) that corresponds to this payload.

It uses actually the Objective-C implementation via the `CommonCrypto` module. 
