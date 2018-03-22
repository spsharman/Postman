# Create Endpoint Group and map to Bridge Domain and VMM Domain

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
    },
    "children": [
      {
        "fvRsDomAtt": {
          "attributes": {
            "classPref": "encap",
            "delimiter": "",
            "encap": "unknown",
            "encapMode": "auto",
            "epgCos": "Cos0",
            "epgCosPref": "disabled",
            "instrImedcy": "lazy",
            "netflowDir": "both",
            "netflowPref": "disabled",
            "primaryEncap": "unknown",
            "resImedcy": "immediate",
            "tDn": "uni/vmmp-VMware/dom-{{vmmDomain}}"
          }
        }
      },
      {
        "fvRsCustQosPol": {
          "attributes": {
            "tnQosCustomPolName": ""
          }
        }
      },
      {
        "fvRsBd": {
          "attributes": {
            "tnFvBDName": "{{bdName}}"
          }
        }
      }
    ]
  }
}
```

Status can be either:
* "status": "created"
* "status": "created,modified"
* "status": "deleted"
