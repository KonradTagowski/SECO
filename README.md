# SECO
SECO: Smart Electronic Component Organizer - Smart Electronic Component Organizer - an easier way to organize electronic components in my home. The project is based on an ESP8266 chip and HT16K33 led driver.

Tech Stack: C++ (Arduino SDK), REST-API/TCP

The project is to build a system for the smart organizer to electronic components. The organizer signals where are elements by an LED located in a specific storage unit.
One shelf from the organizer consists of 64 (8x8) storages. SECO shares API, which gives the user to control LED signaling, download the database with all saved elements with all information about elements, etc. Communication with SECO is available by use of REST-API or TCP connection by specific commands. 
