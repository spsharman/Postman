# Create Application Profile

https://{{APIC}}/api/mo/.json?rsp-subtree=modified - adding ?rsp-subtree=modified to the url will show the created objects

``` json
{
  "fvAp": {
    "attributes": {
      "descr": "",
      "dn": "uni/tn-{{tnName}}/ap-{{apName}}",
      "name": "{{apName}}",
      "nameAlias": "",
      "ownerKey": "",
      "ownerTag": "",
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
