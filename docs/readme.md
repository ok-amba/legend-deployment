## Connections

### Test

DMZTST3911.ok.dk,55002 (kundereplika, distribution, tms)
DMZTST3913.ok.dk,55001/ 172.21.39.13 (Appservice) | G4 Kunde replika (kundereplika, distribution, kundeservice)
OKUDV3260.ok.dk,55001 (distribution, profil)
G4 - https://OKTST32109.ok.dk:8058/Kundeservice/KundeProfileService/Profile/ (profil)



# Current issues

## Test

# Notes, todos and concerns

* Chauffoermelding prod has custom ingress
* Support for redirects (search (some false))

* Search and replace all urls for services and keycloak when done

* Grafana with AD
* Make "Test description" to send to teams with what they should test and things to look out for (url change, app reg urls, changes since migration, decide urls (choose wisely))

* Make "uses gatekeeper secret" - TEST AND MERGE
* Grafana dashboards


* Keycloak/gatekeeper/auth todos
    * Keycloak realms "Web origins" needs new urls export/import
    * Keycloak theme
    * Fix SAML and Redirect URLs on App regs for KC
  * keycloak and gatekeeper secrets
  * Update URLs on all App Registrations



# Defaults:

* Prometheus: true
* Container port: 80


