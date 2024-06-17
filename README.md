# filamux-proto

protobuf definitions for filamux communication

## Frame format

| Start | Type    | Length  | Data            | CRC        |
|-------|---------|---------|-----------------|------------|
| 0x7E  | uint8_t | uint8_t | uint8_t[length] | CRC16-CCIT |
|       |         |         |                 |            |

Types defined in filamux.MessageType enum.
