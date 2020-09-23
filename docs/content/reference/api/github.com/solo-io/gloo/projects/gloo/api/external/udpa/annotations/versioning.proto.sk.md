
---
title: "versioning.proto"
weight: 5
---

<!-- Code generated by solo-kit. DO NOT EDIT. -->


### Package: `udpa.annotations` 
#### Types:


- [VersioningAnnotation](#versioningannotation)
  



##### Source File: [github.com/solo-io/gloo/projects/gloo/api/external/udpa/annotations/versioning.proto](https://github.com/solo-io/gloo/blob/master/projects/gloo/api/external/udpa/annotations/versioning.proto)





---
### VersioningAnnotation



```yaml
"previousMessageType": string

```

| Field | Type | Description | Default |
| ----- | ---- | ----------- |----------- | 
| `previousMessageType` | `string` | Track the previous message type. E.g. this message might be udpa.foo.v3alpha.Foo and it was previously udpa.bar.v2.Bar. This information is consumed by UDPA via proto descriptors. |  |





<!-- Start of HubSpot Embed Code -->
<script type="text/javascript" id="hs-script-loader" async defer src="//js.hs-scripts.com/5130874.js"></script>
<!-- End of HubSpot Embed Code -->