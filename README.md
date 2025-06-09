# Hcaptcha

Sprawdź ważność tokena Hcaptcha; po prostu bez zależności.

## Zainstalować

```
Instalacja npm -Save hcaptcha
```

## Stosowanie

```JS
const {verify} = wymaga („hcaptcha”);

const secret = „My Hcaptcha Secret z hcaptcha.com”;
const token = „token z widżetu”;

weryfikować (tajny, token)
  .Ten ((data) => {
    if (data.success === true) {
      console.log („Success!”, Data);
    } w przeciwnym razie {
      console.log („weryfikacja nie powiodła się”);
    }
  })
  .Catch (console.error);
```
