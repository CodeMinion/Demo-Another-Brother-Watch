# another_brother_watch

Sample project using another_brother on a Wear OS device.

## Deploying to TicWatch
This section covers the steps to deploy to a TicWatch, you'll need at least one WiFi network configured in your device.

### Enable Developer Mode
- Go to Settings
- Go to About
- Find the Build number row and tap it seven times until the developer mode toast appears

### Connect to the TicWatch through Wifi
- Go to Settings
- Go to Developers Options
- Toggle Debug over Wi-Fi (remember the IP address)
- On your computer terminal run: adb connect <ip address with port from previous step> 
- Accept connection on watch.

### Pair RJ-4250WB To Watch
- Go to Settings
- Go to Connectivity
- Go to Bluetooth
- Search for your RJ-4250WB (make sure the printer is configured for Bluetooth Classic)
- Pair to your RJ-4250WB when found on the list.

You should now be able to see your watch in Android Studio as a device to connect to. 


