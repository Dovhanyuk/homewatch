NewRemoteSwitch library v1.0.0 (20121229) for Arduino 1.0
Made by Randy Simons http://randysimons.nl/

This library provides an easy class for Arduino, to send and receive signals
used by some common "new style" 433MHz remote control switches.

There are two styles of remote:
 - "old style", which uses switches or a dial to set the house code. Use the
	RemoteSwitch library instead.
 - "new style", which use a button on the receivers to "learn" a signal. Use this
   library.

License: GPLv3. See ./NewRemoteSwitch/license.txt

Latest source and wiki: https://bitbucket.org/fuzzillogic/433mhzforarduino


Installation of library:
 - Make sure Arduino is closed
 - Copy the directory NewRemoteSwitch to the Arduino library directory (usually
   <Sketchbook directory>/libraries/)
   See http://arduino.cc/en/Guide/Libraries for detailed instructions.
 
Default installation demo:
 - Connect the data-out-pin of a 433MHz receiver to digital pin 2. See photo.
  (Note: your hardware may have a different pin configuration!)
 - Start Arduino, and open the example: File -> Examples -> NewRemoteSwitch ->
   ShowReceivedCode or ShowReceivedCodeNewRemote.
 - Compile, upload and run
 - Open serial monitor in Arduino (115200 baud)
 - Press buttons on a 433MHz-remote, and watch the serial monitor
 

Changelog:
NewRemoteSwitch library v1.0.0 (20121229) for Arduino 1.0
 - Support for receiving A-series Klik-aan-klik-uit remote. (NewRemoteReceiver)
 - With examples to test and demonstrate.
