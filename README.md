# Mpesa STK Push Application

This is a Python-based application that integrates with the Safaricom Mpesa API to perform the following operations:
1. Generate an OAuth token.
2. Perform an STK push to request payment from a customer.

The application uses `requests` for making HTTP requests and is built for use in the terminal (no HTML or web interface).

---

## Features
- **Token Generation**: Securely authenticate and generate an OAuth token.
- **STK Push**: Send payment requests directly to customers' phones.

---

## Prerequisites
Before running the application, ensure you have the following:
- Python 3.x installed on your machine.
- `requests` library installed. You can install it using:
  ```bash
  pip install requests
