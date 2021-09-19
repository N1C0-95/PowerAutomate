# Security Flow With Azure Key Valut

### Trigger: Http Request
### Creare su Azure un Secrets
In questo flow per garantire la sicurezza della chiamata è stata usata la action Azure Key Vault. Il valore della key viene recuperato usando il valore name passato nell'header della richiesta. Successivamente il value della key viene confrontato con il value passato nell'header.

![](https://github.com/N1C0-95/PowerAutomate/blob/main/Security%20Flow/SecurityWithAzureKeyVault/Screenshot_AzureSecretKey.png)
