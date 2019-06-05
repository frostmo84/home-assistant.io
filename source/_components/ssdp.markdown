---
layout: page
title: "SSDP"
description: "Discover integrations on the network using the SSDP protocol."
date: 2019-06-02 18:50
sidebar: true
comments: false
sharing: true
footer: true
ha_category:
  - Network
ha_release: 0.94
---

The `ssdp` integration will scan the network for supported devices and services. Discovered integrations will show up in the discovered section on the integrations page in the config panel.

Integrations can opt-in to be found by adding [an SSDP section](https://developers.home-assistant.io/docs/en/next/creating_integration_manifest.html#ssdp) to their manifest.json.

## {% linkable_title Configuration %}

To integrate this into Home Assistant, add the following section to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
ssdp:
```

## {% linkable_title Discovered Integrations %}

The following integrations are automatically discovered by the SSDP integration:

 - Deconz
 - Philips Hue
 - ESP Home
