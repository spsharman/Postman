# Create Endpoint Group

https://{{APIC}}/api/mo/.json?rsp-subtree=modified - adding ?rsp-subtree=modified to the url will show the created objects

``` json
{
  "fvAEPg": {
    "attributes": {
      "descr": "",
      "dn": "uni/tn-{{tnName}}/ap-{{apName}}/epg-{{epgName}}",
      "fwdCtrl": "",
      "isAttrBasedEPg": "no",
      "matchT": "AtleastOne",
      "name": "{{epgName}}",
      "nameAlias": "",
      "pcEnfPref": "unenforced",
      "prefGrMemb": "exclude",
      "prio": "unspecified",
      "status": "{{status}}"
    }
  }
}
```

Status can be either:
* "status": "created"
* "status": "created,modified"
* "status": "deleted"
