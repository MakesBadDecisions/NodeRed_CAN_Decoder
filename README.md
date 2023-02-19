I know things like this have been created not only in the open source world but also in the retail world. Problem with those is none of them do what I need. I need a simple embedded device to send and recieve CAN messages to then control various outputs. Ideally a simple APP or website to control and veiw these things and allow for simple controls. This project has come from a need based on swapping new drivetrains in older vehicles. These new GM engine and trans mission controllers do not output fan controls, PRNDL conrols nor do they easily produce signals for gauges. In performaning numerous swaps I have been almost forced to use far more prodcuts than I believe neccesarry to accomplish simple controls of simple analog systems. Plus, I have expaned my knowledge base further than I have ever thought.


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
