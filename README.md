# API interfaces sonnen-Batterie

GET

| API-Call    | Supported battery models | Details |
| ----------- |:------------------------:| -------:|
| http://\<IP\>:8080/api/inverter | Eco 8.0 | [Details](details_inverter.md) |
| http://\<IP\>:8080/api/powermeter | Eco 8.0 | TBD |
| http://\<IP\>:8080/api/battery | Eco 8.0 | [Details](details_battery.md) |
| http://\<IP\>:8080/api/v1/status | Eco 8.0 | TBD |
| http://\<IP\>:80/api/v2/status | Eco 8.0 | TBD |
| http://\<IP\>:8080/api/battery_system | Eco 8.0 | TBD - (Empty response, Use-Case?)|
| http://\<IP\>:8080/api/ios | Eco 8.0 | TBD |
| http://\<IP\>:80/api/v2/latestdata | Eco 8.0 | TBD - (Requires authentification by token) |
| http://\<IP\>:80/api/v2/configurations/\<config\> | Eco 8.0 | TBD - (Requires authentification by token)|

PUT

| API-Call    | Supported battery models | Details |
| ----------- |:------------------------:| -------:|
| http://\<IP\>:80/api/v2/configurations/\<config\> | Eco 8.0 | TBD - (Requires authentification by token) |

POST

| API-Call    | Supported battery models | Details |
| ----------- |:------------------------:| -------:|
| http://\<IP\>:80/api/v2/setpoint/discharge/{watt} | (Not tested yet) | TBD |
| http://\<IP\>:80/api/v2/setpoint/charge/{watt} | (Not tested yet) | TBD |

# Webhooks

TBD
