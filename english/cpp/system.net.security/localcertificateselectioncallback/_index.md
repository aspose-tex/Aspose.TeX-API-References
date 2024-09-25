---
title: System::Net::Security::LocalCertificateSelectionCallback typedef
linktitle: LocalCertificateSelectionCallback
second_title: Aspose.TeX for C++
description: 'System::Net::Security::LocalCertificateSelectionCallback typedef. A user delegate used to select local SSL certificate in C++.'
type: docs
weight: 700
url: /cpp/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


A user delegate used to select local SSL certificate.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = 
    System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>(
        System::SharedPtr<Object>, String,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>,
        System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>,
        System::ArrayPtr<String>)>
```

## See Also

* Namespace [System::Net::Security](../)
* Library [Aspose.TeX for C++](../../)
