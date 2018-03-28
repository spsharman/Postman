# Get all Application Profiles in a Tenant

https://{{APIC}}/api/node/mo/uni/tn-{{tnName}}/.json?query-target=children&target-subtree-class=fvAp

## Example query

```
https://{{APIC}}/api/node/mo/uni/tn-Ciscolive/.json?query-target=children&target-subtree-class=fvAp
```

## Example output

``` json
{
    "totalCount": "3",
    "imdata": [
        {
            "fvAp": {
                "attributes": {
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-Ciscolive/ap-App_1",
                    "extMngdBy": "",
                    "lcOwn": "local",
                    "modTs": "2018-03-04T10:32:53.002+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "App_1",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "prio": "unspecified",
                    "status": "",
                    "uid": "15374"
                }
            }
        },
        {
            "fvAp": {
                "attributes": {
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-Ciscolive/ap-App_2",
                    "extMngdBy": "",
                    "lcOwn": "local",
                    "modTs": "2018-03-04T10:33:14.763+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "App_2",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "prio": "unspecified",
                    "status": "",
                    "uid": "15374"
                }
            }
        },
        {
            "fvAp": {
                "attributes": {
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-Ciscolive/ap-App_3",
                    "extMngdBy": "",
                    "lcOwn": "local",
                    "modTs": "2018-03-04T10:33:39.958+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "App_3",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "prio": "unspecified",
                    "status": "",
                    "uid": "15374"
                }
            }
        }
    ]
}
```
