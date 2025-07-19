# Epever-MPPT-to-Home-Assistant

# Home Assistant integration of Epever Mppt all model with Modbus TCP on rs485 serial port.

To make the integration work, you must replace the following values in the code:

- converter IP address
- converter port

# example code:

<img width="823" height="449" alt="example" src="https://github.com/user-attachments/assets/1edfbff1-5838-4150-ac1f-46dcd60c7594" />

# rs485 to eth or wifi converter

I recommend using this one, but you can use any similar device:


<img width="572" height="562" alt="elfin" src="https://github.com/user-attachments/assets/f1947e7a-7c67-455f-a785-c343964e288e" />


https://a.aliexpress.com/_EzQiFGI


# settings :

<img width="952" height="913" alt="serial_settings" src="https://github.com/user-attachments/assets/1f7b7136-58ba-4ab4-8651-734c2f19a6a4" />


<img width="952" height="872" alt="communication_settings" src="https://github.com/user-attachments/assets/0c28b70c-0d65-432e-b9cc-76e52f4adfc1" />


# Epever Communication Port :


<img width="720" height="164" alt="epever_port" src="https://github.com/user-attachments/assets/7ae46f99-8263-4f11-b097-6c374a4d6728" />


# The converter can be powered directly from the communication port of the epever MPPT by connecting correctly as shown in the diagram.

# Warnings :

If you use your epever MPPT with the epever app and therefore with a Wi-Fi or Ethernet dongle connected to the epever, it is not possible to connect the elfin converter simultaneously as stable multiple communication is not provided in the epever software.
Therefore, if you need to have two devices reading data from the epever, you will need to purchase the "RS485-1M2S Extension Module," which manages data traffic and enables multiple communication.


<img width="582" height="526" alt="epever_rs485_1m2s" src="https://github.com/user-attachments/assets/0eb9119b-8628-4182-b8e4-f0dc3cd0cfa9" />


<img width="861" height="400" alt="epever_rs4851m2s_port" src="https://github.com/user-attachments/assets/bac10252-1c89-4fe9-a9dd-d8858a76ad41" />

<img width="835" height="456" alt="epever_rs4851m2s_port_2" src="https://github.com/user-attachments/assets/d7d476c6-62c1-4aa6-acbc-26d54dcf2aca" />





