# 🧭 STM32F407G Discovery 6-Month Learning Roadmap

> From beginner → embedded engineer | 2 hours/day | 6 months  
> Learn C, STM32 HAL, FreeRTOS, and build IoT projects.

## 📘 What’s inside
- `roadmap_6months.md` → full learning plan  
- `projects/` → project files for each month  
- `logs/` → your weekly progress and notes  

## 💡 Goal
By the end of this roadmap, you will:
- Write STM32 code in HAL & register level  
- Build FreeRTOS-based applications  
- Create IoT projects with sensors, SD card, Bluetooth  

---

📈 *Keep committing your progress each week!*  
Example:
```bash
git commit -m "Week 3 done: GPIO interrupt + UART log"


---

### 🧩 `roadmap_6months.md`
(dán toàn bộ kế hoạch này vào file này)

```markdown
# 🧭 6-Month STM32F407G Discovery Roadmap

## 📅 Month 1 – C Fundamentals + STM32 Setup
🎯 Goal: Master basic C, CubeIDE, GPIO, UART.

| Week | Topics | Practice |
|------|---------|----------|
| 1 | C basics, setup environment | Blink LED |
| 2 | Arrays, pointers, functions | swap(), sum_array() |
| 3 | GPIO + HAL | Button toggle LED |
| 4 | UART | UART “Hello STM32” |

🧩 Mini Project: LED button + UART log

---

## 📅 Month 2 – Advanced C + Peripherals
🎯 Goal: Structs, typedef, ADC, PWM, timer interrupt.

| Week | Topics | Practice |
|------|---------|----------|
| 5 | Struct, typedef, enum | LED struct manager |
| 6 | Timer & PWM | LED fade |
| 7 | ADC read | Analog sensor |
| 8 | Combine UART + ADC | Smart LED light |

🧩 Mini Project: “Smart light adjusts brightness with ADC”

---

## 📅 Month 3 – SPI, I2C, DMA & C modules
🎯 Goal: Master communication and modular coding.

| Week | Topics | Practice |
|------|---------|----------|
| 9 | SPI basics | SPI loopback |
| 10 | I2C + MPU6050 | Read accel/gyro |
| 11 | DMA | UART DMA continuous TX |
| 12 | Modular coding | LED library |

🧩 Mini Project: Data Logger mini (MPU6050 + UART DMA)

---

## 📅 Month 4 – FreeRTOS
🎯 Goal: Understand RTOS multitasking, queue, semaphore.

| Week | Topics | Practice |
|------|---------|----------|
| 13 | Task creation & priorities | LED + UART tasks |
| 14 | Queue & delay | Inter-task communication |
| 15 | Semaphore & mutex | UART + ADC shared resource |
| 16 | Advanced features | Task notify, event groups |

🧩 Mini Project: “Sensor Station” (multi-task FreeRTOS)

---

## 📅 Month 5 – Real-world Application
🎯 Goal: Integrate sensors + FreeRTOS + communication.

| Week | Topics | Practice |
|------|---------|----------|
| 17 | I2C OLED display | Show temperature |
| 18 | Bluetooth UART | Send sensor data |
| 19 | Combine FreeRTOS + Bluetooth | Multi-thread control |
| 20 | Build Smart Sensor Node | Complete system |

🧩 Mini Project: “Smart Sensor Node” (DHT22 + OLED + BT)

---

## 📅 Month 6 – Register-level + Final Project
🎯 Goal: Learn low-level register coding, optimize system.

| Week | Topics | Practice |
|------|---------|----------|
| 21 | CMSIS GPIO register | Blink by register |
| 22 | Timer register & interrupt | PWM via register |
| 23 | Debug & optimization | ITM, SWV, CPU usage |
| 24 | Final Project | IoT Data Logger Pro |

🧩 Final Project: FreeRTOS + SD + Bluetooth + DMA Logger

---
