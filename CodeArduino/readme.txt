Hướng dẫn nạp code vào NodeMCU

1) Cài Arduino IDE (https://www.arduino.cc/en/Main/Software)
2) Tiến hành cập nhật driver cho chip CP2102 (pololu-cp2102 or CP210x-Uni..)
3) Add thư viện board esp8266 : File -> Preferences -> Thêm đường dẫn 'http://arduino.esp8266.com/stable/package_esp8266com_index.json' vào ô 'Additional Boards Manager URLs:' -> OK
4) Install thư viện trên : Tools -> Board: -> Broads Manager.. -> Tìm và cài đặt thư viện 'esp8266 by ESP8266 Community'
5) Cập nhật thư viện cho giao tiếp MQTT (pubsubclient-master.zip): Sketch -> Include Library -> Add .ZIP Libraty -> Chọn file 'pubsubclient-master.zip'
6) Chọn board NodeMCU để sử dụng thư viện ESP8266WiFi.h
7) Nạp code 'onlyPub' cho sensor 
8) Nạp code 'onlySub' cho actuator
