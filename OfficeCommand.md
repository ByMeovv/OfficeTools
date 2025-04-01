(link to install software)[https://otp.landian.vip/en-us/downdload.html]

---
# Install code

```
.\setup.exe /configure .\configuration-Office2021Enterprise.xml
```


```
reg add "HKCU\Software\Microsoft\Office\16.0\Common\ExperimentConfigs\Ecs" /v "CountryCode" /t REG_SZ /d "std::wstring|US" /f
```
* If u want to install Ru Office - change Language ID in `*.xml` file `en-us` to `ru-ru` in first and second `Language ID`.
---
# Activation code

```
irm https://get.activated.win | iex
```

* Choose
  `2-1`
