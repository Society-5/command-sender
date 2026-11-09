# command-sender

The bridge between the [VR-interface](https://github.com/Society-5/VR-interface) and the robot. It turns the user's actions in virtual reality into JSON commands and sends them over UDP to [robot-controller](https://github.com/Society-5/robot-controller), which drives the WowWee Robosapien X over infrared.

Message format, as expected by robot-controller on port 9999:

```json
{"type": "action", "action": "go_forward"}
```

Status: planned. No source code has been committed yet.

---

Part of **[Society-5](https://github.com/Society-5)**: a WowWee Robosapien X that explores a floor on its own, using a phone camera and QR codes as markers, with a mixed-reality (VR) interface for remote control. See [Introduction](https://github.com/Society-5/Introduction) for the project overview.
