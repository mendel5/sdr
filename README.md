# sdr
Software defined radio

## Overview
Theoretical use cases. Not intended for practical application.

### FM broadcasting
- Radio, terrestrial, analog
- also known as UKW-Radio
- VHF-Band II, 87.5 - 108 MHz
- https://de.wikipedia.org/wiki/UKW-Rundfunk
- https://de.wikipedia.org/wiki/Ultrakurzwelle#Verwendung_des_UKW-Frequenzspektrums
- https://en.wikipedia.org/wiki/Band_II
- https://de.wikipedia.org/wiki/H%C3%B6rfunk
- https://learn.adafruit.com/getting-started-with-rtl-sdr-and-sdr-sharp/sdr-number-fm-radio
- SDRsharp / SDR#

### DABplus
- Radio, terrestrial, digital
- also known as DAB+
- VHF-Band III, 174.160 - 229.840 MHz
- https://de.wikipedia.org/wiki/Digital_Audio_Broadcasting
- https://de.wikipedia.org/wiki/T-DAB-Frequenz
- https://de.wikipedia.org/wiki/VHF-Band_III
- https://de.wikipedia.org/wiki/Liste_der_DAB-Sender_in_Deutschland
- https://github.com/AlbrechtL/welle.io
- https://github.com/JvanKatwijk/qt-dab
- https://qirx.softsyst.com/

### DVB-T
- Television, terrestrial
- also known as DVB-T / DVB-T2
-  470 - 690 MHz
- https://de.wikipedia.org/wiki/DVB-T2
- https://de.wikipedia.org/wiki/DVB-T2_HD
- https://www.hauppauge.de/site/products/data_solohd.html
- https://www.hauppauge.de/site/products/data_dualhd.html
- https://www.hauppauge.de/site/products/data_wintv_v10.html

### DVB-S
- Television, satellite based
- also known as DVB-S / DVB-S2
- Satellite frequency: 10.7 - 11.75 GHz or 11.8 - 12.75 GHz
- LNB: 950 - 2175 MHz
- https://de.wikipedia.org/wiki/DVB-S
- https://de.wikipedia.org/wiki/Rauscharmer_Signalumsetzer
- https://de.wikipedia.org/wiki/Satellitenrundfunk
- https://www.hauppauge.de/site/products/data_nova-s2.html
- https://www.hauppauge.de/site/products/data_wintv_v10.html

### Air band
- also known as Flugfunk
- 108 - 137 MHz
- 108 - 117.95 MHz, 50 kHz steps: reserved for navigational aids
- 118 - 136.975 MHz, 25 kHz steps, AM
- 117.975 - 137 MHz
- https://de.wikipedia.org/wiki/Flugfunk
- https://en.wikipedia.org/wiki/Airband
- https://skyvector.com/airports
- SDRsharp / SDR#

### ADS-B
- Aircraft positioning
- 1090 MHz
- https://de.wikipedia.org/wiki/Automatic_Dependent_Surveillance
- https://www.rtl-sdr.com/adsb-aircraft-radar-with-rtl-sdr/
- https://www.rtl-sdr.com/signalseverywhere-ads-b-aircraft-tracking-with-rtl-sdr-dump1090-and-virtual-radar-server/
- https://www.virtualradarserver.co.uk/
- https://github.com/antirez/dump1090
- https://globe.adsbexchange.com/
- https://www.flightradar24.com
- https://www.radarbox.com
- https://flightaware.com/live/
- https://github.com/adsbxchange/adsb-exchange
- https://github.com/jprochazka/adsb-receiver

### Marine band
- Marine VHF radio
- 156 - 162 MHz
- https://de.wikipedia.org/wiki/Mobiler_Seefunkdienst_(Ultrakurzwelle)
- https://en.wikipedia.org/wiki/Marine_VHF_radio

### AIS
- Marine vessel positioning
- AIS 1: 161.975 MHz (Kanal 87B)
- AIS 2: 162.025 MHz (Kanal 88B)
- https://de.wikipedia.org/wiki/Automatic_Identification_System
- https://www.rtl-sdr.com/rtl-sdr-tutorial-cheap-ais-ship-tracking/
- https://www.marinetraffic.com
- https://www.vesselfinder.com
- https://news.ycombinator.com/item?id=26625908
- https://github.com/OpenCPN/OpenCPN
- https://openmarine.net/openplotter

### GNSS
- General positioning
- GPS, Galileo, Glonass, Beidou
- https://de.wikipedia.org/wiki/Globales_Navigationssatellitensystem
- https://www.rtl-sdr.com/rtl-sdr-tutorial-gps-decoding-plotting/
- https://gnss-sdr.org/
- https://github.com/gnss-sdr/gnss-sdr
- https://www.onesdr.com/list-of-gnss-frequency-and-accuracy/

### Weather station
- Local consumer weather station
- 433 MHz or 868 MHz
- https://www.kompf.de/weather/rtlsdrsensor.html
- https://github.com/skaringa/weather-sdr-decode

### Amateur radio
- also known as HAM radio
- 144 - 146 MHz
- 430 - 440 MHz
- https://de.wikipedia.org/wiki/Amateurfunkdienst
- https://en.wikipedia.org/wiki/Amateur_radio
- https://de.wikipedia.org/wiki/Notfunk
- https://de.wikipedia.org/wiki/2-Meter-Band
- https://de.wikipedia.org/wiki/70-Zentimeter-Band

### Citizens band radio
- also known as CB-Funk
- 26.565 - 27.405 MHz (80 channels)
- https://de.wikipedia.org/wiki/CB-Funk
- https://en.wikipedia.org/wiki/Citizens_band_radio
- CB-Funk vs. Amateurfunk: http://www.jan-pawlowski.de/funktechnik.html , https://www.amateurradio.uni-halle.de/glossary/funk-faq.de.html

## Todo
- Weather fax / satellite (NOAA)

## Related things
- Television: DVB-C
- IPTV
- IP Radio
- Streaming / Mediathek

## Links
### Wikipedia
- https://en.wikipedia.org/wiki/Software-defined_radio
- https://en.wikipedia.org/wiki/Electromagnetic_spectrum
- https://de.wikipedia.org/wiki/Elektromagnetisches_Spektrum
- https://en.wikipedia.org/wiki/Radio_spectrum
- https://de.wikipedia.org/wiki/Frequenzband

### General
- https://www.rtl-sdr.com/about-rtl-sdr/
- https://www.rtl-sdr.com/category/applications/
- https://www.rtl-sdr.com/tag/applications-2/
- https://site.ieee.org/wnc/files/2014/04/IEEE_Frady_SDR_Mar_2014.pdf
- https://www.reddit.com/r/RTLSDR/comments/9gp9yp/more_things_to_do_with_an_sdr/
- https://www.rs-online.com/designspark/10-things-you-can-do-with-software-defined-radio
- https://www.ard-digital.de/
- https://satellitenempfang.info
- https://airspy.com/download/ SDRsharp / SDR#
- https://www.onesdr.com/
- https://www.onesdr.com/2020/01/15/what-is-software-defined-radio-used-for/
- https://support.nooelec.com/hc/en-us/articles/360005807694-NESDR-SMArt-Series
- http://www.csgnetwork.com/antennaedcalc.html
- https://wiki.ubuntuusers.de/Gqrx/

### Youtube
- [Youtube: Getting Started with the RTL-SDR (Software Defined Radio) - ModernHam](https://www.youtube.com/watch?v=C01wLvwjLIs)
- [Youtube: The Coolest Radio You've Probably Never Heard Of - Tom the Dilettante](https://www.youtube.com/watch?v=h4x7cGALaC8)
- [Youtube: The Beginner's Guide To Software Defined Radio RTL-SDR - Tech Minds](https://www.youtube.com/watch?v=nB6XQSEFwVA)
- [Youtube: 5 Cool Things You Can Do With An RTL SDR Receiver - Tech Minds](https://www.youtube.com/watch?v=9QzklSyKqQM)
- [Youtube: 5 Cool Things You Can Do With An AIRSPY SDR Receiver - Tech Minds](https://www.youtube.com/watch?v=Zq12KeRSx8Y)
- [Youtube: Installing RTL-SDR & SDR Sharp on Win10 Made Easy - TheSmokinApe](https://www.youtube.com/watch?v=rUwRt5qn-6U)
- [Youtube: How does Software Defined Radio (SDR) work under the Hood? SDR Tutorial #286](https://www.youtube.com/watch?v=xQVm-YTKR9s)
- [Youtube: 2020 SDR Guide Ep 1 : The Incredible World of Software Defined Radio (RTL-SDR, Airspy, SDRPlay etc.)](https://www.youtube.com/watch?v=RWeWALpmtQQ)

### Reddit
- https://www.reddit.com/r/RTLSDR/
- https://www.reddit.com/r/sdr/
- https://www.reddit.com/r/amateurradio/
- https://www.reddit.com/r/HamRadio/
- https://www.reddit.com/r/rfelectronics/
- https://www.reddit.com/r/amateursatellites/
- https://www.reddit.com/r/ADSB/
