# Get all Contexts (VRFs)

https://{{APIC}}/api/node/class/fvCtx.json

## Example output

``` json
{
    "totalCount": "16",
    "imdata": [
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-Ciscolive/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-11-24T14:03:01.319+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "2195456",
                    "seg": "2195456",
                    "status": "",
                    "uid": "15374"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-iomart/ctx-vrf-02",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-07-27T13:43:38.812+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-02",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "2785281",
                    "seg": "2785281",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-rwhitear/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-07-11T19:11:07.375+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2260993",
                    "seg": "2260993",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-mgmt/ctx-inb",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-14T07:59:21.989+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "inb",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "3047424",
                    "seg": "3047424",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-common/ctx-default",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-14T07:59:21.735+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "default",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2654208",
                    "seg": "2654208",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-common/ctx-copy",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-14T07:59:21.735+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "copy",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "2686976",
                    "seg": "2686976",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-iomart/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-07-19T15:55:53.780+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2260994",
                    "seg": "2260994",
                    "status": "",
                    "uid": "15194"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-ssharman/ctx-vrf-02",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-07-17T10:20:54.097+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-02",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "3080193",
                    "seg": "3080193",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-mgmt/ctx-oob",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-14T07:59:21.989+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "oob",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "16386",
                    "scope": "2097152",
                    "seg": "2097152",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-common/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2018-03-04T10:28:06.461+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "32770",
                    "scope": "3080192",
                    "seg": "3080192",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-infra/ctx-overlay-1",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-14T07:59:19.664+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "overlay-1",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "32770",
                    "scope": "16777199",
                    "seg": "16777199",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-ssharman/ctx-vrf-04",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2018-02-05T09:47:44.700+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-04",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2097155",
                    "seg": "2097155",
                    "status": "",
                    "uid": "15374"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-ssharman/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-06-16T20:11:41.382+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2785280",
                    "seg": "2785280",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-ssharman/ctx-vrf-03",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2017-07-17T12:47:03.722+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-03",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2097153",
                    "seg": "2097153",
                    "status": "",
                    "uid": "17846"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-infra/ctx-ave-ctrl",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2018-03-09T06:02:07.444+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "ave-ctrl",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "32770",
                    "scope": "2818049",
                    "seg": "2818049",
                    "status": "",
                    "uid": "0"
                }
            }
        },
        {
            "fvCtx": {
                "attributes": {
                    "bdEnforcedEnable": "no",
                    "childAction": "",
                    "descr": "",
                    "dn": "uni/tn-micdoher/ctx-vrf-01",
                    "extMngdBy": "",
                    "knwMcastAct": "permit",
                    "lcOwn": "local",
                    "modTs": "2018-03-15T13:19:30.703+00:00",
                    "monPolDn": "uni/tn-common/monepg-default",
                    "name": "vrf-01",
                    "nameAlias": "",
                    "ownerKey": "",
                    "ownerTag": "",
                    "pcEnfDir": "ingress",
                    "pcEnfDirUpdated": "yes",
                    "pcEnfPref": "enforced",
                    "pcTag": "49153",
                    "scope": "2785283",
                    "seg": "2785283",
                    "status": "",
                    "uid": "15374"
                }
            }
        }
    ]
}
```
