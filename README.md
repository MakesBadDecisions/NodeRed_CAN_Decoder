I know things like this have been created not only in the open source world but also in the retail world. Problem with those is none of them do what I need. I need a simple embedded device to send and recieve CAN messages to then control various outputs. Ideally a simple APP or website to control and veiw these things and allow for simple controls. This project has come from a need based on swapping new drivetrains in older vehicles. These new GM engine and transmission controllers do not output fan controls, PRNDL controls nor do they easily produce signals needed when performing these swaps. In performaning numerous swaps I have been almost forced to use far more products than I believe neccesarry to accomplish simple controls of simple analog systems. Im not doing this to make money, I am doing this to make my life easier and to learn new skills that apply to many other facets of life. In this journey I have expaned my knowledge base further than I have ever thought possible. I started this project almost 2 years ago. Since then I have learned 3d modeling, 3d printing, 3d scanning, learned about electronics at the small level, some coding skills, used various SBC's, automated most of my house, built many things to replace broken parts around my house and vehicles, made all kinds of neat and interesting tools, toys, art, functional things and most of all had fun learning the entire time.  

What I envision is an ESP32 device, appropriate voltage and noise controls, CAN interface and mosfet controlled high amperage 12volt control of various automotive circuits. I have seen where node-red can be run on the ESP32, I just have been unsuccesful at this point. So for now during this phase the raspi4 will have to be the test mule.


There are many things to get done on this readme and I will get it done. 

You will need in your pallette:

    node-red-contrib-socketcan
  
    node-red-contrib-uibuilder
  
    node-red-contrib-xterm
  
    and all other raspi related nodes.

Hardware Currently Being Used :
  
    USB2CAN from Inno-Maker - https://www.inno-maker.com/product/usb-can/
  
    Raspi4 - new install from latest Raspi release then fully updated and upgraded. CAN-utils installed, NodeJS updated, Node-Red updated
  
    GM E38 Bench Test unit
  
    HPTuners MPVI2
  
    ECU Simulator - https://www.tindie.com/products/kevinliang/obd-ii-ecu-simulator-2/

OBD2 Wiki - https://en.wikipedia.org/wiki/OBD-II_PIDs

List Of things on to-do list - not in any specific order :
    
    - Gauges - Updating and functioning
    
    - Define and Decode more PIDs 
    
    - Request, Read and Clear Codes from Ui
    
    - Request and Read Vehicle Information from Ui
    
    - User Definable warning from UI to trigger internally defined GPIO and resultant output function - ie shift light, fan relay trigger based on temps, etc.
    
    - CAN request "gate-keeper" of sorts - This is to make sure that no CAN requests are sent at same time. This feature will be needed before real world use.
    
    - A freaking sweet and beutiful UI with gauges, user definable controls and functions - I have no idea how to do any of this so please if you are interested in this project please help as much as you can.







Thanks for everything and taking the time to look at this
