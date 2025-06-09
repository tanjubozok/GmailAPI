# GmailAPI

Bu proje, C# ile Gmail API üzerinden e-posta gönderme, alma ve okuma işlemlerini kolayca yapabilmenizi sağlayan basit bir örnek uygulamadır. OAuth 2.0 kimlik doğrulaması ile güvenli bir şekilde Google hesabınıza erişebilir, e-postalarınızı programatik olarak yönetebilirsiniz.

## Özellikler

- Gmail API ile e-posta gönderme
- Gelen kutusunu listeleme ve e-posta okuma
- OAuth 2.0 üzerinden güvenli kimlik doğrulama
- Basit ve anlaşılır C# kod yapısı
- Kolay entegrasyon ve özelleştirme imkânı

## Gereksinimler

- .NET 6 veya üzeri
- Google Cloud Console’da oluşturulmuş bir OAuth 2.0 Client ID
- [Google.Apis.Gmail.v1](https://www.nuget.org/packages/Google.Apis.Gmail.v1) NuGet paketi

## Kurulum

1. Google Cloud Console üzerinden bir proje oluşturun ve Gmail API’yi etkinleştirin.
2. OAuth 2.0 istemci kimliğinizi oluşturun ve `credentials.json` dosyasını indirin.
3. Proje dizinine `credentials.json` dosyasını ekleyin.
4. Gerekli NuGet paketlerini yükleyin:
    ```
    dotnet add package Google.Apis.Gmail.v1
    ```
5. Projeyi derleyip çalıştırın.

## Kullanım

- E-posta göndermek, listelemek ve okumak için örnek kodları kullanabilirsiniz.
- Kimlik doğrulama işlemi ilk çalıştırmada otomatik olarak yapılır ve gerekli izinler istenir.

## Lisans

MIT Lisansı
