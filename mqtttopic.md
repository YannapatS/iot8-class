## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301019/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301019/model-01/sn-001
    - payload
        - {"Temperature": "25.2"}
        - {"Humidity": "60"}
        - {"Speed_Motor": "388"}
        - {"Water_Quality": "10"}
        - {"Water_Flow": "15"}
        - {"Water_Level": "4"}
        - {"Water_Pressure": "100"}
        - {"DoorLock": "Lock"}
        - {"Airflow": "100"}

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301019/model-01/sn-001
    - payload
        - {"Temperature": "25.5"}
        - {"Humidity": "75.5"}
        - {"Vibration": "0.5"}
        - {"Balance": "Yes"}
        - {"Water_Leak: "No"}





