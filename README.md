### Robot Army
Demo IoT project for showing how we can use a Bluetooth connected device(MiP Robot) from a web interface
with [CylonJS](https://cylonjs.com/)

#### Installation
*Ubuntu*
`sudo apt-get install libbluetooth-dev`
`npm install -g cylon-ble`
`npm install`

*Mac*
`npm install`

*Discover MiP Device Id*
Run the scan below and look for the _WowWee-MiP-xxx_ peripheral device and copy the UUID.
`sudo cylon-ble-scan`
