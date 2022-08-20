# Vending

## Interface
On Arduino UNO
with RFID, I2C LCD, One External Interrupt(Rising edge), UART(to Server)

Tag card and checking customer infor mation.

Select product and push purchase button, product information appears(Name, Purchase availability, Price)



## Server
On ATmega128A
with Blutooth(FB155BC, UART), UART(to Interface)

Database(Customer match to card number, Product stock, information)
Send message to blutooth
