# API Schnittstellen sonnen-Batterie

GET:
- http://<IP>:8080/api/inverter
- http://<IP>:8080/api/powermeter
- http://<IP>:8080/api/battery
- http://<IP>:8080/api/v1/status
- http://<IP>:80/api/v2/status
- http://<IP>:8080/api/battery_system (Aktuell bzw. bei mir leere Antwort, Use-Case?)
- http://<IP>:8080/api/ios
- http://<IP>:80/api/v2/latestdata (Nur mit Token-Authentifizierung)
- http://<IP>:80/api/v2/configurations/<config> (Nur mit Token-Authentifizierung), <config> =
  - EM_OperatingMode
  - NVM_PfcFixedCosPhi
  - NVM_PfcIsFixedCosPhiActive
  - NVM_PfcIsFixedCosPhiLagging
  - EM_ToU_Schedule

PUT:
- http://<IP>:80/api/v2/configurations/<config> (Nur mit Token-Authentifizierung), <config> =
  - EM_OperatingMode
  - NVM_PfcFixedCosPhi
  - NVM_PfcIsFixedCosPhiActive
  - NVM_PfcIsFixedCosPhiLagging
  - EM_ToU_Schedule

POST
- /api/v2/setpoint/discharge/{watt} (Noch nicht getestet)
- /api/v2/setpoint/charge/{watt} (Noch nicht getestet)
