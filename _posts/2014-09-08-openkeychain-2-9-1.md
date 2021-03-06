---
layout: post
title: OpenKeychain 2.9.1 and 2.9.2
---

As promised, we are now releasing as early and often as possible™.

## 2.9.1
  * Split encrypt screen into two
  * Fix key flags handling (now supporting Mailvelope 0.7 keys)
  * Improved passphrase handling
  * Key sharing via SafeSlinger
  * Yubikey: preference to allow other PINs, currently only signing via the OpenPGP API works, not inside of OpenKeychain
  * Fix usage of stripped keys
  * SHA256 as default for compatibility
  * Intent API has changed, see [https://github.com/open-keychain/open-keychain/wiki/Intent-API](https://github.com/open-keychain/open-keychain/wiki/Intent-API)
  * OpenPGP API now handles revoked/expired keys and returns all user ids
  
## 2.9.2
  * Fix keys broken in 2.9.1
  * Yubikey decryption now working via API

[Google Play](https://play.google.com/store/apps/details?id=org.sufficientlysecure.keychain) | [F-Droid](https://f-droid.org/app/org.sufficientlysecure.keychain)

## Yubikey NEO support
Some more notes regarding Yubikey NEO support:

  * Currently it only works when using the API, i.e., when signing/decrypting something from K9 alpha or one of the other [compatible apps](http://www.openkeychain.org/apps/).
  * By default the PIN 123456 is used to access the Yubikey. You can also use a different PIN by changing the PIN via GnuPG and disabling the preference to use the default one in OpenKeychain.
  * We are working hard to also allow the usage of Yubikeys from the encrypt and decrypt screens inside of OpenKeychain