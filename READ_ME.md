Perform security audit
    1. Default passwords
        - Changed default passwords Advanced > Primary Network > 2.5 GHz > Password > 5.0 GHz > Password
        ![Default_pass](Screenshots/WIFI_Hardening_Default_Pass.png)
        ![Default_pass](Screenshots/WIFI_Hardening_2.4_SSID_Pass.png)
    2. Default SSID Advanced > Primary Network > 2.5 GHz > SSID > 5.0 GHz
        - Changed default SSID. Decided to keep SSId broadcast according to this article https://support.apple.com/en-us/102766. Disabling SSId will cause devices to constantly broadcast probe requests when away from home network, potentially exposing devices to malicious actors.
        - Kept wifi settings at WPA2 so non-WPA3 enabled devices can still connect
        ![My Image](images/my-image.png)
    3. Guest network
        - Created guest network segregated from main network
        ![My Image](images/my-image.png)
    4. Disable WPS
        - Unsecure due to PIN code needed to connect.
        ![My Image](images/my-image.png)
    5. Disable UPnP
        - UPnP unsecure due to ability to quickly connect to network and considered authorized for network
        ![My Image](images/my-image.png)

DNS Settings

Device Monitoring

Network Diagram

Home security Write Up.