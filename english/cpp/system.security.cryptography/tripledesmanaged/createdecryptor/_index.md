---
title: System::Security::Cryptography::TripleDESManaged::CreateDecryptor method
linktitle: CreateDecryptor
second_title: Aspose.TeX for C++
description: 'System::Security::Cryptography::TripleDESManaged::CreateDecryptor method. Creates decryptor object with explicit parameters in C++.'
type: docs
weight: 200
url: /cpp/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Creates decryptor object with explicit parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Encryption key in byte array form. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Initial value in byte array form. |

### ReturnValue

Newly created decryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.TeX for C++](../../../)
## TripleDESManaged::CreateDecryptor() method


Creates decryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.TeX for C++](../../../)
