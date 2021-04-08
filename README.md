# Oculess

## Features
- Remove Oculus / FaceBook account
- Disable telemetry

## Tutorial

### Remove Account
1. Click on "DISABLE COMPANION"
2. Click "OK"
3. Choose “Companion Server” from the List
4. Click “Deactivate this device admin app”
5. Restart your Quest

### Disable Telemetry
```diff 
!Warning! You won't be able to remove this app without a factory reset after running the following command
```
1. Run this command ```adb shell dpm set-device-owner com.bos.oculess/.DevAdminReceiver```
2. Click on "DISABLE TELEMETRY" in the app