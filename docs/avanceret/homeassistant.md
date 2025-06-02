# Integration med Home Assistant

Du kan sende GPS- og sensor-data til Home Assistant via MQTT.

## Eksempel på integration

1. MQTT-opsætning
2. Sensor payload i HA:
```yaml
sensor:
  - platform: mqtt
    name: "Meshtastic GPS"
    state_topic: "meshtastic/your-node"
    value_template: "{{ value_json.position.latitude }}"
```