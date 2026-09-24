<img width="1024" height="576" alt="image" src="https://github.com/user-attachments/assets/327a472c-a984-4489-a9fd-d6017bf5a423" />

## Overview

The RFID Smart Billing System is an embedded systems project developed using the LPC2148 (ARM7) microcontroller. The system automates product billing by identifying RFID-tagged products, displaying product information on an LCD, communicating with a Linux PC over UART, retrieving product information from a database, and generating the final bill.

This project demonstrates practical implementation of embedded firmware, serial communication, hardware interfacing, and Linux integration.

---

## Features

- RFID-based product identification
- Automatic billing process
- LCD display for product details
- UART communication with Linux PC
- Linux-based product database
- Real-time bill generation
- Faster and error-free billing

---

## Technologies Used

| Hardware | Software |
|----------|----------|
| LPC2148 (ARM7) | Embedded C |
| RFID Reader | Linux |
| 16x2 LCD | GCC |
| UART | Serial Communication |
| Power Supply | Makefile |

---

## System Architecture
<img width="1024" height="682" alt="image" src="https://github.com/user-attachments/assets/83c61535-74f4-46db-93e7-d32310ca26f2" />


The RFID reader scans the product tag and sends the Tag ID to the LPC2148. The microcontroller processes the request, communicates with the Linux database using UART, receives the product information, displays it on the LCD, and updates the billing data.

---

## Project Workflow

<img width="682" height="1024" alt="image" src="https://github.com/user-attachments/assets/e3718de2-64af-4668-8cd0-05e12c4acf7c" />


### Workflow
<img width="682" height="1024" alt="image" src="https://github.com/user-attachments/assets/a0239769-0019-472e-8330-5be8b9302feb" />


1. Scan RFID Tag
2. Read Tag ID
3. Identify Product
4. Display Product Details
5. Update Linux Database
6. Generate Bill

---

## Hardware 

<img width="1448" height="1086" alt="controller" src="https://github.com/user-attachments/assets/301e5a38-9ce0-4d22-beef-b52df84ebdb5" />

### Hardware Components

- LPC2148 ARM7 Microcontroller
- RFID Reader
- 16×2 LCD Display
- Linux PC
- UART Interface
- 5V Power Supply

---

## UART Communication

The LPC2148 exchanges product information with the Linux PC through UART communication.

Communication Sequence:

- RFID Tag Scanned
- LPC2148 reads Tag ID
- Tag ID sent to Linux
- Linux searches database
- Product details returned
- LCD updated
- Bill generated

## Hardware Required

- LPC2148 Development Board
- RFID Reader Module
- RFID Tags
- 16×2 LCD Display
- USB-UART Converter
- Linux PC
- Power Supply
  
  <img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/757cd883-c5b2-4013-971b-c8655e0a9300" />


---

## Software Required

- Keil uVision
- Flash Magic
- Ubuntu/Linux
- GCC Compiler
- Terminal Software (Minicom / GTKTerm)

---

## How to Run

### Embedded Side

1. Open the project in Keil.
2. Build the project.
3. Generate the HEX file.
4. Flash the LPC2148 using Flash Magic.

### Linux Side
1. Connect the UART cable.
2. Compile the Linux application.
3. Start the database program.
4. Scan RFID tags.
5. View billing information.
<img width="1024" height="368" alt="image" src="https://github.com/user-attachments/assets/1c357a7b-2af8-48dc-8f83-bb5a54832b10" />



---

## Applications

- Smart Retail Stores
- Supermarkets
- Library Management
- Inventory Management
- Warehouse Automation
- Cashless Billing Systems
---

## Future Enhancements

- Barcode Scanner Support
- QR Code Billing
- Wi-Fi Connectivity
- Cloud Database
- Mobile Application
- Online Payment Integration
- Receipt Printing
- IoT Dashboard

---

## Author

**KURVA VARUN KUMAR**

Embedded Systems Engineer

GitHub:
https://github.com/VarunKumar2129/RFID-Smart-Billing-System.git

---

## License

This project is intended for educational and learning purposes.
