# iot-temperature

IOT temperature

## Manually publish to MQTT topic

Using InfluxDB data format:
`mosquitto_pub -t 'sensors/plants' -m 'test,id=foo baz=10'`
