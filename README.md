# SystemyPrzemyslowe
Informatyka Systemów Przemysłowych zadania z - PLC ; SCADA ; RTOS ; ROS ; IoT



---

### **1. Programowanie PLC**
#### **Zadania:**
1. **Sterowanie sygnalizacją świetlną**:  
   - Stwórz program sterujący sekwencją świateł drogowych (zielone, żółte, czerwone) z zachowaniem odpowiednich czasów.
   - Rozszerzenie: Dodaj tryb awaryjny (miganie światła żółtego).

2. **Sterowanie taśmociągiem**:  
   - Zaprogramuj taśmociąg z czujnikami start/stop i wyłącznikiem awaryjnym.  
   - Rozszerzenie: Dodaj detekcję obiektów na taśmie i sortowanie w zależności od ich wielkości.

3. **Regulator temperatury**:  
   - Opracuj program do regulacji temperatury z wykorzystaniem PID (np. grzanie wody w zbiorniku).  
   - Rozszerzenie: Dodaj opcję ręcznej zmiany nastawy (setpoint).

#### **Narzędzia**:
- Symulatory PLC, np. **CODESYS**, **Siemens TIA Portal** z wirtualnym sterownikiem S7-1200.  

---

### **2. SCADA**
#### **Zadania:**
1. **Monitorowanie temperatury**:  
   - Stwórz prosty system SCADA do monitorowania temperatury z symulowanego czujnika.  
   - Wyświetlaj dane na wykresach i generuj alarm, jeśli temperatura przekroczy limit.

2. **Sterowanie prostym procesem**:  
   - Zbuduj wizualizację HMI do sterowania sygnalizacją świetlną lub pompą wodną.  
   - Dodaj przyciski start/stop i wskaźniki stanu.

3. **Integracja z PLC**:  
   - Połącz program SCADA z rzeczywistym (lub symulowanym) sterownikiem PLC i zbieraj dane procesowe w czasie rzeczywistym.

#### **Narzędzia**:
- Oprogramowanie SCADA, np. **Ignition**, **WinCC (Siemens)**, lub darmowe **OpenSCADA**.

---

### **3. RTOS (Real-Time Operating Systems)**
#### **Zadania:**
1. **Zarządzanie zadaniami**:  
   - Stwórz aplikację na RTOS (np. FreeRTOS), w której jedno zadanie monitoruje czujnik, a drugie zapisuje dane do pamięci.

2. **Priorytetyzacja zadań**:  
   - Zaimplementuj system, w którym zadania o różnych priorytetach (np. alarmy, rejestrowanie danych) wykonują się zgodnie z harmonogramem.

3. **Komunikacja między zadaniami**:  
   - Stwórz aplikację wykorzystującą kolejki lub semafory do komunikacji między zadaniami (np. przesyłanie danych czujnika do wyświetlacza).

#### **Narzędzia**:
- **FreeRTOS**, **Zephyr**, lub **ChibiOS**. Symulator QEMU do testów.

---

### **4. ROS (Robot Operating System)**
#### **Zadania:**
1. **Symulacja robota mobilnego**:  
   - Zbuduj w Gazebo prostą symulację robota, który porusza się po zadanej trajektorii.  
   - Rozszerzenie: Dodaj przeszkody i obsługę ich unikania.

2. **Publikowanie i subskrypcja tematów**:  
   - Stwórz prosty system ROS, w którym jeden węzeł publikuje dane czujnika, a drugi węzeł odbiera je i wykonuje akcję (np. wydruk na konsoli).

3. **Mapowanie i lokalizacja (SLAM)**:  
   - Zaimplementuj algorytm SLAM do tworzenia mapy środowiska robota.  
   - Rozszerzenie: Użyj ROS Navigation Stack do autonomicznego poruszania się robota.

#### **Narzędzia**:
- ROS Noetic/ROS2 Foxy, symulator Gazebo.

---

### **5. IoT**
#### **Zadania:**
1. **Monitoring środowiska**:  
   - Stwórz system IoT do monitorowania temperatury i wilgotności (np. z wykorzystaniem DHT22 i ESP32).  
   - Dane przesyłaj do chmury (np. ThingSpeak, AWS IoT).

2. **Sterowanie urządzeniem przez MQTT**:  
   - Stwórz system, w którym użytkownik zdalnie steruje urządzeniem (np. zapala/wyłącza diodę LED).  
   - Użyj brokera MQTT, np. Mosquitto.

3. **Zdalny monitoring procesów przemysłowych**:  
   - Opracuj system IoT do monitorowania pracy taśmociągu. Wyświetlaj dane w aplikacji webowej.

#### **Narzędzia**:
- ESP32/ESP8266, Raspberry Pi, platformy IoT (AWS IoT, ThingSpeak, Adafruit IO).

---

### **Czy warto dodać coś jeszcze?**
Podane dziedziny stanowią solidną bazę dla informatyka systemów przemysłowych. Możesz się na nich skupić, a w miarę postępów dodawać inne obszary, takie jak analiza danych przemysłowych, cybersecurity w OT (Operational Technology), czy protokoły komunikacyjne (np. OPC UA, PROFINET).
Jeśli opanujesz podstawy tych dziedzin, warto pomyśleć o:
1. **Cybersecurity w OT**: Nauka zabezpieczania systemów przemysłowych (np. firewall dla PLC, certyfikaty TLS w IoT).  
2. **Przetwarzanie danych przemysłowych**: Kursy o bazach danych (SQL, InfluxDB) oraz analiza danych w Pythonie (NumPy, pandas).  
3. **Protokoły komunikacyjne**: OPC UA, PROFINET, EtherCAT – kluczowe w systemach przemysłowych.  
