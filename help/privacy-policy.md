---
layout: page
title: Privacy Policy
---

> You don't have to take our word on all of this. OpenKeychain is an open source project. Anyone can study the source code and make an informed decision.

### We do not run infrastructure

OpenKeychain is an app that provides end-to-end encryption for other protocols, such as email.
We do not run infrastructure or provide cloud services.

### Keyservers

Public keys created in OpenKeychain can be uploaded to public keyservers.
These are not run by us and thus we are not responsible for them.
By default the [keys.openpgp.org](https://keys.openpgp.org/) is used.

Please see their [privacy policy](https://keys.openpgp.org/about/privacy) if you are uploading your keys.

### Permissions

OpenKeychain requests certain permissions to provide full functionality. More precisely, it may request permission to use the device's camera, access the addressbook, or access files on your device.

Data aquired using these permissions is **not** shared with cloud services.

  * The **camera** permission is required to scan QR Codes.
  * Accessing the **contacts** is required to link keys to contacts in your address book. **This is done offline.**
  * Access to **files** on your device is requested to open existing files for encryption or decryption.

