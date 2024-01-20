# Barkinator-Official

This windows terminal application uses RESTAPIs of RUCKUS products to perform automated assessments. 

Below are the current capabilities

-  SmartZone
   - Best Practice Wireless Configuration Assessment
        
- RUCKUS One
  - Best Practice Wireless Configuration Assessment




  


**Best Practice Wireless Configuration Assessment**

- Limitations
  - Does general configuration assessment and not specific application or situational assessments like low density, high density, most coverage, load balancing, etc. Just initial deployment best practice.
  - Does NOT automatically change anything. The report will need to be analyzed and used to manually change configurations
  - RUCKUS One versions supported: all
  - SmartZone versions supported: 5.2 - 6.1
  - RUCKUS One assessment analyzes venue settings only, so individual AP configurations will need to be manually reviewed and adjusted
  - Need prime/admin level access
  - Best practices are based on North American wireless regulations
  - Assesses indoor radio channel configurations only
  - Analyzes 2.4 and 5GHz radio
  - Below are all the configurations that are analyzed for best practice setting
    - AP Zone/Venue
      - Historical connection failures)
      - Smart Monitor
      - Recover SSID
      - Channel Range (2.4)
      - Channel (2.4)
      - Auto Cell Sizing (2.4)
      - Channelization Width (2.4)
      - Auto Cell Sizing (2.4)
      - Background Scanning Frequency (2.4)
      - Auto Channel Selection (2.4)
      - Allow DFS Channels (5)
      - Channel Range (5)
      - Channel (5)
      - Auto Cell Sizing (5)
      - Channelization Width (5)
      - Background Scanning Frequency (5)
      - Auto Channel Selection (5)
    - WLAN
      - 802.11k Neighbor Report
      - 802.11d
      - Proxy ARP
      - WiFi 6/7
      - OFDM Only
      - BSS Min Rate
