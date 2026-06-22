# UHUB
I wanted to make a super portable USB hub that literally just looks and feels like a standard USB thumb drive, but actually gives you 2x USB-A ports.

I actually went through three different prototypes before I went onto this design. One of the earlier versions included an SD card adapter, and another one had two USBC ports instead. None of them fit the compact form factor I was going for, so I scraped them and stuck with this dual USBA setup.

The biggest learning curve on this project was the electronics. Originally, I thought I could just use a basic microcontroller to handle the data routing but I quickly found out that it doesn't work like that for a proper USB hub. I had to change my way entirely, ditch that idea and use a dedicated USB hub controller chip instead to get everything working properly.

BOM in the Excel sheet.

## Images
<img width="675" height="350" alt="{8ECC3E5E-1F54-4FDA-B8DA-64C9F2C356B1}" src="https://github.com/user-attachments/assets/b98ccce6-09c7-4281-89a7-3d424d8a5512" />
<img width="1057" height="276" alt="{5F473140-6CA8-4659-8276-5225413C16E2}" src="https://github.com/user-attachments/assets/f00d9a6d-9d50-4d94-ade0-28c4b14f558e" />
<img width="837" height="511" alt="{FC316DAE-BF99-4434-94F4-58B127979E6F}" src="https://github.com/user-attachments/assets/6b962843-a6f3-4cf0-ac03-c5c3805aa5b3" />
