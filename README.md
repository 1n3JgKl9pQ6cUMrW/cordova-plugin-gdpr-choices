# Cordova Plugin Gdpr Choices (cordova-plugin-gdpr-choices)

Google User Messaging Platform (UMP) SDK gdpr choices.

## Install on Cordova
```bash
cordova plugin add https://github.com/MrRotella/cordova-plugin-gdpr-check.git
```

### USE
- isGdpr (promise)
    ```bash
    cordova.Gdpr.isGdpr()
    ```
    - Return JSON object:
        ```bash
        {
            success: true/false (false cannot check),
            value: -1/0/1 (-1 cannot check,0 Gdpr not applies,1 if Gdpr applies),
            message        
        }
        ```
- canShowAds (promise)
    ```bash
    cordova.Gdpr.canShowAds()
    ```
    - Return JSON object:
        ```bash
        {
            success: true/false (false cannot check),
            value: true/false,
            message        
        }
        ```
- canShowPersonalizedAds (promise)
    ```bash
    cordova.Gdpr.canShowPersonalizedAds()
    ```
    - Return JSON object:
        ```bash
        {
            success: true/false (false cannot check),
            value: true/false,
            message        
        }
        ```
    