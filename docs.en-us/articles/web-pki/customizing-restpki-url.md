﻿# Custom RestPKI configuration

On the article [Get started](get-started.md), we saw that the [`init()`](https://docs.lacunasoftware.com/content/typedocs/web-pki/classes/_lacuna_web_pki_d_.lacunawebpki.html#init) code must be called before any other method is called:

```javascript
pki.init(onWebPkiReady);
```
If a non-standard PKI Rest is used, other than https://pki.rest It is necessary to configure the RestPKI URL that will be used in the `init()` call.

```javascript
pki.init({
    restPkiUrl: 'https://YourRestPKI.com/',
    ready: onWebPkiReady,
});
```

> [!NOTE]
> If WebPKI is not being used in conjunction with RestPKI, this setting is unnecessary.

For more information about the arguments passed to the [`init()`](https://docs.lacunasoftware.com/content/typedocs/web-pki/classes/_lacuna_web_pki_d_.lacunawebpki.html#init), please refer to the
[method's documentation](https://docs.lacunasoftware.com/content/typedocs/web-pki/classes/_lacuna_web_pki_d_.lacunawebpki.html#init).
