## Features

## Topics

- 구조
    - 1안 : publisher/subscriber/type
    - 2안(채택) : globalTopic(msgRoom)/publisher/type/target(#)
  
- Global Topics(msgRoom)
    - node-mdk : 강의실 서버

- publisher & target
  - tablet
  - kiosk
  - node-mdk
  - all(target only)
  - {추가 가능}

- 키오스크
    - node-mdk/sensor/state
    - node-mdk/{장비명}/msg
    - kiosk/all/msg
    -

- 관제실용 장비
    - obServer/{강의실명(서버)}/state
    - obServer/{강의실명(서버)}/msg


## Messages
- sensor
  ````json
    {
      "lecturePC" : "online",
      "temperature": 24.5,
      "humidity": 60,
      "co2": 400
    }

  ````
- node-mdk/msg
  ````json
  {
    "msg": "",
    "timestamp": 172039320,
    "duration" : {
      "day" : 0,
      "hour" : 0.5,
      "min" : 30
     }
  }
  ````

## Getting started

## Usage

```dart

const like = 'sample';
```

## Additional information
