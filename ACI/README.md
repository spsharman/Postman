# ACI Posts

A collection of various APIC posts that I use on a regular basis

```
POST https://{{APIC}}/api/aaaLogin.json
POST https://{{APIC}}/api/mo/.json?rsp-subtree=modified
GET  https://{{APIC}}/api/node/class/{{class}}.json
```

I use a number of variables so that the posts can be used with Runner to push bulk configuration.

Variable  | Description
--------|-------------------------
apName  | Application Profile name
bdName  | Bridge Domain name
epgName | Endpoint Group name
status  | created/modified/deleted  
tnName  | Tenant name  
vrfName | VRF/Context name
