# Volca Simple
Use any midi keyboard to trigger samples in the Korg Volca Sample using an arduino as a midi channel re-router.

# Requirements:

<strong>Hardware:</strong><br>
*Korg Volca Sample <br>
*Arduino Uno or Mega <br>
*Midi In:  <br>
   &nbsp;&nbsp;-Female MIDI jack Digikey CP-2350-ND <br>
   &nbsp;&nbsp;-220Ohm 1/4watt resistor Digikey CF14JT220RCT-ND <br>
   &nbsp;&nbsp;-1N4148 diode Digikey1N4148-TAPCT-ND <br>
   &nbsp;&nbsp;-10kOhm 1/4watt resistor Digikey CF14JT10K0CT-ND <br>
   &nbsp;&nbsp;-470 Ohm 1/4watt resistor Digikey CF14JT470RCT-ND (I used 2x220 instead) <br>
   &nbsp;&nbsp;-6N138 optocoupler Digikey 751-1263-5-ND <br>
 <br>
*Midi Out: <br>
   &nbsp;&nbsp;-Female MIDI jack <br>
   &nbsp;&nbsp;-220 ohm resistor <br>
   &nbsp;&nbsp;-Wires  <br>
   <br>
<strong>Software:</strong> <br>
 *Arduino MIDI library http://playground.arduino.cc/Main/MIDILibrary <br>


#Setup
* To recieve Midi messages with Arduino follow the next tutorial: http://www.instructables.com/id/Send-and-Receive-MIDI-with-Arduino/step10/Receive-MIDI-Messages-with-Arduino/
* To send Midi messages with Arduino follow the next tutorial: http://www.instructables.com/id/Send-and-Receive-MIDI-with-Arduino/#step1
* Install Arduino MIDI library http://playground.arduino.cc/Main/MIDILibrary
* Upload the Volca_Simple file to your Arduino
* Have Fun
