### Please note that this is a fork of [Toucan-sam](https://github.com/Toucan-Sam/VoEnabler).

I'm updating it whenever possible for my OP5. I have no other devices to validate the module. 

## VoEnabler
This module enables the VoLTE & VoWiFi & RCS options by editing `build.prop`.

**Important:** VoLTE/VoWiFi will not work if your carrier doesn't support it, even if you install this module.

## Devices
<br>OnePlus 5
<br>Redmi Note 7 Pro
<br>

XDA Thread: [here](https://forum.xda-developers.com/apps/magisk/module-v4-volte-enabler-t3649613)
<br>Guide to **_maybe_** make this work: [here](https://forum.xda-developers.com/oneplus-5t/how-to/guide-volte-vowifi-german-carriers-t3817542)

## What does this module change?
<br>persist.data.iwlan.enable=true
<br>persist.dbg.ims_volte_enable=1 
<br>persist.dbg.volte_avail_ovr=1 
<br>persist.dbg.vt_avail_ovr=1
<br>persist.dbg.wfc_avail_ovr=1
<br>persist.radio.rat_on=combine
<br>persist.radio.data_ltd_sys_ind=1
<br>persist.radio.data_con_rprt=1
<br>persist.radio.calls.on.ims=1
<br>persist.dbg.ims_volte_enable=1
<br>persist.dbg.volte_avail_ovr=1
<br>persist.dbg.vt_avail_ovr=1
<br>persist.dbg.wfc_avail_ovr=1
<br>persist.data.iwlan=1
<br>persist.data.iwlan.ipsec.ap=1
<br>persist.radio.volte.dan_support=true
<br>persist.radio.rat_on=combine
<br>persist.radio.data_ltd_sys_ind=1
<br>persist.radio.data_con_rprt=1
<br>persist.radio.calls.on.ims=1
<br>persist.radio.VT_ENABLE=1
<br>persist.sys.cust.lte_config=true
<br>persist.rcs.supported=1

## Changelog
<br>2020-04-04 (v1.8): Update Module & Test devices
<br>2020-04-04 (v1.7): Update VoLTE & WoWIFI & RCS 
<br>2020-02-02 (v1.6): Update template for Magisk v20.x
<br>2019-04-05 (v1.5): Update template for Magisk v19.x
<br>2018-11-25 (v1.4): Removed some white space that may cause issues.
<br>2018-09-19 (v1.3): Update template for Magisk v17.x
<br>2018-04-09 (v1.2): Update template for Magisk v15.x
<br>2017-08-02 (v1.1): Removed "persist.data.iwlan.enable=true" as this was reported to break WiFi calling on some carriers.
<br>2017-08-01 (v1): Switched from using service.sh to system.prop
<br>2017-07-31 (Beta): Initial commit.
