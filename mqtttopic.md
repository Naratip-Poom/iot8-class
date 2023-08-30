## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"Water temperature": "25.2"}
        - {"WATER LEVEL SENSOR": "120"}
        - {"Fabric Detection": "1"}
        - {"Weight measurement": "20"}
        - {"Foam Detection": "2"}
        - {"water flow sensor": "1"}
        - {"pressure measuremer sensor": "3"}
        - {"Filter clogging": "2"}
        - {"Tachometer sensor": "5"}
        - {"Air-flow sensor": "4"}
        - {"noise anomaly detection": "40"}
        - {"detect clogged filter": "1"}
        - {"imbalance": "22"}
        - {"Liquid flow": "2"}
        - {"Air quality measurement": "4"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"Acoustic Sensor": "1"}
        - {"Vibration Sensor": "20"}
        - {"washing machine lid magnet sensor": "0"}
        - {"count people": "4"}



