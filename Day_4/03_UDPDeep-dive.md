# 03_UDPDeep-dive

[TCPDeep-dive 👉VIDEO &#128279;](https://codered.eccouncil.org/courseVideo/practical-wireshark?lessonId=b0a64e26-2be7-4f69-b119-1998409fefcf&finalAssessment=false)

- UDP
  - No guarantee data arrives at all
  - No error-checking and correction provided
  - 8 bytes header
  - Faster than TCP
  - Divides bits into datagrams or packets
  - Best for applications that require speed (online streaming, video games)

**UDP Header**
|Source Port|Destinatin Port|
|---|---|
|2 bytes| 2 bytes |
| 2 bytes | 2 bytes |
