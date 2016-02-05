DSA815 Screen Shot via LAN
==========================

DSA815 supports native socket communication via port 5555 (undocumented).

This command use it to simplify communication and get more speed.

<img src="https://lh3.googleusercontent.com/mMyt_RQ4DnDbjDd2bNQ4oPH2_UEMIgbf4AQAs1HqwDcGrqa4OTtW8IGAZsfRapN6XxT2Y5DMkL7x7Jh1GFKg9YJv-RXk7yA5xdzrtLzfDEtYg0rdlVlbLrd4HcqFNb_ZSfR9hKxD4HdfKjJJU41__F8rfk4DHkmXn8eCmnLqesYKEZUYOik4gyfb_ClUpskfWjmTbzr5W20cNsEgT1AYZLXKqnsY5ZaNtVCvuYzzHPp8YKa2Wq19CpIucezHiGcrR2GO4pHOHKVkU3AEawIEE2hIFMGDMxHDK2HEj0CraVjCQ2po4KplFBPkQ-7HSC--vtn-eQ2c5w2iqVs14-tvIpm6eh2_NE9lNLpxcRMMprGF2tihJpX4fmhmvBK3Ow9ntNTcrj4LMFxentCj06r5S5urgsu4yg9O2AromX7DczuLIMbh7pLilex8dzN2b6p5k8gw2yElDHOjOqjMeGOfI5bubf20F1vQ8D3FADAI1OmI29WiQu8B7sMULCom7KwNj47hSJUSKGxANDG_udxr-lr2Fc6WMHWAPHDaMK7H2yRSRdmUXLQPU-bhhP9KWkp0ZOBV7w=w800-h439-no"/>

## Usage

```
dsa815 --host=192.168.0.10 --format=png
```

## RC file

```
# ~/.dsa815rc
@opts[:host] = '192.168.0.72'
```

# Firmware version

Firmware 1.15 does not respond to dns-sd by default.
So you must specify ip address or set mDNSDiscovery option.

## Ref.

 * dns-sd -B _lxi._tcp / dns-sd -B _scpi-raw._tcp
 * http://hostname/lxi/identification (is announcing port number) invalid xml
