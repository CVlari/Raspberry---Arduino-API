# Raspberry-Arduino-tempLogging


Created this communication between raspberry and arduino to visualize temperatures of 3d printer enclousure. Arduino side includes the lcd 16 digit screen
and 2 temperature sensors, DHT11 & DHT22. These sensors are placed in the different sectons of the cabinet, one is for the filament layer and 
other is for the actual 3d printer layer.

Raspberry and arduino are communicating between USB. Raspberry also retvieves outside temperature data with a API call.
