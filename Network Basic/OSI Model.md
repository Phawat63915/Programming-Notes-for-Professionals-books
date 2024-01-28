# OSI Model หรือ Open Systems Interconnection Model
เป็นโมเดลในการอธิบายการสื่อสารข้อมูลระหว่างคอมพิวเตอร์ โดย OSI Model จะแบ่งการสื่อสารออกเป็น 7 ชั้น (layer) เพื่อให้การสื่อสารข้อมูลระหว่างอุปกรณ์ต่างๆ ในเครือข่ายเป็นไปอย่างมีประสิทธิภาพและปลอดภัย

แต่ละชั้นของ OSI Model จะมีหน้าที่และบทบาทที่แตกต่างกันออกไป ดังนี้

1. Physical layer (ชั้นฟิสิกส์) - ชั้นที่ต่ำสุดของ OSI Model ซึ่งเป็นชั้นที่รับและส่งสัญญาณแบบดิจิตอล/อนาล็อกไปยังอุปกรณ์อื่นๆ โดยมีข้อมูลเป็นสัญญาณไฟฟ้า สัญญาณไร้สาย หรือสัญญาณอื่นๆ
> [1 Physicl: Physical structure > Coax ,Fiber, Wiresless, Hub, Repeaters]

2. Data Link layer (ชั้นเชื่อมต่อข้อมูล) - ชั้นที่มีหน้าที่จัดการกับข้อมูลในรูปแบบของ frame และส่งต่อไปยังชั้นที่สูงกว่า
> [2 Data Link: Frames > Ethernet, PPP, Switch, Bridge]

3. Network layer (ชั้นเครือข่าย) - ชั้นที่จัดการกับการส่งข้อมูลระหว่างเครือข่ายต่างๆ โดยใช้โปรโตคอลระดับส่วนของ Internet Protocol (IP)
> [3 Network: Packets > IP, ICMP, IPSec, IGMP]

4. Transport layer (ชั้นขนส่ง) - ชั้นที่จัดการกับการส่งข้อมูลระหว่างโปรแกรมที่ทำงานบนเครื่องคอมพิวเตอร์ โดยใช้โปรโตคอลระดับส่วนของ Transmission Control Protocol (TCP) หรือ User Datagram Protocol (UDP)
> [4 Transport: End-to-end connections > TCP, UDP]

5. Session layer (ชั้นเซสชัน) - ชั้นที่จัดการกับการสร้างและสรวจสอบเซสชันในการสื่อสารข้อมูล โดยใช้โปรโตคอลระดับส่วนของ Session Control Protocol
> [5 Session: Synch & send to port > API's, Socket, WinSock]

6. Presentation layer (ชั้นนำเสนอ) - ชั้นที่จัดการกับการแปลงรูปแบบของข้อมูล เช่น การเข้ารหัส/ถอดรหัส การบีบอัด/ขยายขนาด ฯลฯ
> [6 Presentation: Syntax layer > SSL, SSH, IMAP, FTP, MPEG, JPEG]

7. Application layer (ชั้นแอปพลิเคชัน) - ชั้นสุดท้ายของ OSI Model ซึ่งมีหน้าที่จัดการกับโปรแกรมและการใช้งานต่างๆ เช่น การส่งอีเมล์ (Email), การใช้งานเว็บเบราว์เซอร์ (Web browser), การสื่อสารผ่านแชท (Instant messaging), การโอนไฟล์ (File transfer) ฯลฯ
> [7 Appliction: End User Layer > HTTP, HTTPS, FTP, SSH, DNS]

# References
[TH]
- https://aoostudio.com/system-infrastructure/osi-model-open-systems-interconnection-model-%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3/

[US]
- https://www.guru99.com/layers-of-osi-model.html
- https://www.researchgate.net/figure/The-logical-mapping-between-OSI-basic-reference-model-and-the-TCP-IP-stack_fig2_327483011

(Keywords)
- https://www.google.com/search?q=OSI+Models