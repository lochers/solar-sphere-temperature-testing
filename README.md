# Testing Workflow
---
Steps:
- Open UART connection on pheripheral UART1 (baud 9600)
- Wait for the the data logger to send a byte (0xXX i.e. don't care)
- Query the temperature probe
- Send the data to the data logger as a 32 bit float
- Repeat

The temperature sensor tested in this branch is the TMP1075
