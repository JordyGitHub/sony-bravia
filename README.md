# Sony Bravia TV - Domoticz Python plugin
Domoticz Python plugin for Sony Bravia TV

This plugin uses the Sony Bravia RC API by Antonio Parraga Navarro https://github.com/aparraga/braviarc.

## Information
The plugin will show information from your Sony Bravia TV in Domoticz.
It will work on Sony Bravia models 2013 and newer. Not tested on Sony Bravia with Android yet (that will probably need simple IP control)!

## Sony Bravia plugin instructions
Works with Pre-Shared Key (PSK). The default PSK you can use is 'sony', but you can change the PSK to something else. If you change it, remember to also change the PSK in the Domoticz hardware page.

### Prerequisites:
* Enable remote start on your TV: [Settings] => [Network] => [Home Network Setup] => [Remote Start] => [On]

* Enable pre-shared key on your TV: [Settings] => [Network] => [Home Network Setup] => [IP Control] => [Authentication] => [Normal and Pre-Shared Key]

* Set pre-shared key on your TV: [Settings] => [Network] => [Home Network Setup] => [IP Control] => [Pre-Shared Key] => sony

* Give your TV a static IP address, or make a DHCP reservation for a specific IP address in your router.

* Determine the MAC address of your TV: [Settings] => [Network] => [Network Setup] => [View Network Status]

The IP address, PSK and MAC address need to be entered in the Domoticz hardware page, see screenshot below.

![sony_tv](https://cloud.githubusercontent.com/assets/11230573/24884147/6fc63ec8-1e48-11e7-95aa-0020bcf6b666.png)

![sony_tv_vol](https://cloud.githubusercontent.com/assets/11230573/24884199/a0c53394-1e48-11e7-8d2f-2b4c0d417173.png)

![sony_tv_sources](https://cloud.githubusercontent.com/assets/11230573/24884202/a23478e8-1e48-11e7-85a4-51d0ef3a3e32.png)

![sony_tv_plugin_hardware](https://cloud.githubusercontent.com/assets/11230573/24884146/6fc5ce16-1e48-11e7-8d9a-ca7d4db8a7b8.png)