---
title: System::Security::Cryptography::RSACryptoServiceProvider::Decrypt method
linktitle: Decrypt
second_title: Aspose.TeX for C++
description: 'System::Security::Cryptography::RSACryptoServiceProvider::Decrypt method. Decrypts message. Not implemented in C++.'
type: docs
weight: 900
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Decrypts message. Not implemented.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) to decrypt. |
| use_oaep | bool | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### ReturnValue

Decrypted data array.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.TeX for C++](../../../)
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Decrypts input data using the specified padding mode.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) array to decrypt. |
| padding | SharedPtr\<RSAEncryptionPadding\> | Padding mode. |

### ReturnValue

Decrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.TeX for C++](../../../)
