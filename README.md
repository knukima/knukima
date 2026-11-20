## Build authenticity

All my Android release builds are signed with my own keys. To verify that a build is mine, compare the SHA-256 fingerprints below with the certificates in the build.

- **Release key** – OTA package signing · [Certificate](certs/releasekey.x509.pem)  
  **SHA-256**: `6C:E1:A7:1C:CF:69:FF:6D:13:4C:EE:71:A1:4E:95:B7:39:86:61:D9:91:A6:10:AC:78:6F:3B:75:50:43:B5:58`

- **Platform key** – System apps · [Certificate](certs/platform.x509.pem)  
  **SHA-256**: `0C:FD:CD:69:B5:4B:60:1A:02:58:A9:24:DB:9B:18:3B:41:4E:A2:A1:AC:F5:95:EE:87:F0:DB:E1:22:E2:F8:D3`

Both certificates are valid from **17 Nov 2026** to **4 Apr 2054**.