# CanDuino
its a Can enabled Arduino, Can...Duino


Make sure to take The most recent version for projects.
Check The issues page for any know issues and if they have been fixed or not.

Onve the board has been made, follow these instructions to program

If you only partily follow these along with other internet suggestions then I don't care if you fail or break the board.
Follow these fully and nothing else. If it still doesn't work, THEN go use the internet.

1) BOOTLOADING

  a) get another arduino board
  
  b) upload the blink sketch to it (VERY IMPORTANT TO DO THIS AND CONFIRM YOU FOUND A WORKING BOARD)
  
  c) upload the ArduinoISP sketch to your now working arduino
  
  d) disconeect all boards from the computer
  
  e) conect wires as follows (Orginal Arduino -> New Canduino):
  
      5V -> 5V
      
      GND -> GND
      
      SCK -> SCK
      
      MISO -> MISO
      
      MOSI -> MOSI
      
      Pin10 -> RESET  
      
      
  f) make sure the settings in the IDE are:
  
      Board: Arduino/Genuino UNO
      
      Port: The one it connects to
      
      Programmer: "Arduino as ISP"
      
      
  g) connect the Working Arduino (that is not coneected to the new Canduino) to the computer
  
  h) click burn bootloader
  
  i) when done disconnect the USB and all wires between the boards
  
2) UPLOADING CODE

  a) conect the new bootloaded Canduino to the computer via USB
  
  b) open you sketch
  
  c) change the board to "Arduino Pro or Pro Mini"
  
      Select "ATmega 329P (5V, 16 MHZ)" as the Processor
      
  d) upload
  
  e) enjoy
  
