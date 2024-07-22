# PIX_API

The Pix QR Code Generator API allows you to generate QR Codes compatible with the instant payment system Pix, from the Central Bank of Brazil. This API is ideal for integrating QR Code generation functionality into payment systems, e-commerce, banking apps, and more.

Features:
Customize parameters such as amount, Pix key, description, and more.
API Documentation
Endpoints
1. Generate Static QR Code
URL: /api/qrcode/static

Method: POST

Parameters:

name (string): Name of the recipient.
pix_key (string): Recipient's Pix key (CPF, CNPJ, email, phone number, or random key).
amount (string): Transaction amount.
city (string): Recipient's city.
txt_id (string): Transaction identifier.
directory (string, optional): Directory to save the generated QR Code.
