# TYPO


# First entry ~5Hr 50Min (28/08/2026)
So this is my first time journaling on GitHub , kind of forgot that I need to do this and I'll completed my whole keyboard PCB , but worry not I'm gonna explain each and every part till now. I do have a lapse [recoding](https://lapse.hackclub.com/timelapse/QEk8M2VW-hlY) of the whole session  .

I started by browsing and finalize the form factor and layout.

<img  alt="6eace1fa9e6ed97d95f48941d8bc81a" src="https://github.com/user-attachments/assets/24f9dbe2-dc09-4ab7-b48e-2e7657a62fd3" style="width:300px; height:300px; object-fit: contain;"/>

This is it 80% keyboard containing 79 keys and a rotary encoder , it has a perfect balance of compact and functional keyboard. 
After finalizing layout, I started calling the docs, installed MARBASTLIB I started the work on schematic.
I started by adding all the keys required and rest of the component like raspberry pi pico , diode , EC11 , mounting holes , stabilizers & finally SK6812 MINI-E RGB leds , yeah its going to be a RGB keyboard !!. 
Then I learned about how matrices work , whats ghosting is and how to correct it with a diode from [this guide](https://www.dribin.org/dave/keyboard/one_html/) .

After completing the connections of all the components and placed the RGB LEDs into another page so that it doesn't look that messy. 

<img width="825" height="566" alt="Screenshot 2026-08-29 at 12 15 36 AM" src="https://github.com/user-attachments/assets/232bb4c8-72b5-48e4-80aa-c36cdbbdefd4" />

Later, I also added some capacitors of 100nf 0603 to each row of the keyboard to give some consistency power supply .
Also a custom made touch pad.


Then I started on the PCB. After updating from the schematic, it was a huge mess so I figure out another way to arrange them properly. There is a plug-in for keypad, specially for kicad are used to that and generated my layout on [this](https://www.keyboard-layout-editor.com) .

<img width="884" height="358" alt="keyboard-layout" src="https://github.com/user-attachments/assets/a0f66f36-cb7d-4e4e-b686-8704a13e1236" />

The exported the Json file and use the plug-in to arrange the keys LED and diodes in the proper layout with many tweek and iterations. 

I placed the EC11 just beside the functional keys and then followed by the raspberry pi pico.
There was an empty space below the pico so I thought of adding a custom-made touchpad and did that.
And after completing the wiring and everything here is the PCB.

<img width="653" height="326" alt="Screenshot 2026-08-29 at 12 28 17 AM" src="https://github.com/user-attachments/assets/1e76629e-1321-4167-8d37-b9bd6ef1ec89" />

<img width="652" height="318" alt="Screenshot 2026-08-29 at 12 28 23 AM" src="https://github.com/user-attachments/assets/5c925ed5-4f9c-4a6a-8193-b97c95581bf2" />

<img width="974" height="486" alt="Screenshot 2026-08-29 at 12 29 35 AM" src="https://github.com/user-attachments/assets/8c84f691-4cb6-4171-8046-39693eeef799" />

<img width="1014" height="439" alt="Screenshot 2026-08-29 at 12 29 59 AM" src="https://github.com/user-attachments/assets/1beb2128-5273-475a-9b7b-a63dadebfcc4" />





By the way, I also added silkscreen on the back side of the PCB (the straw hat crew).

<img width="950" height="358" alt="Screenshot 2026-08-29 at 12 30 21 AM" src="https://github.com/user-attachments/assets/0ae50051-80a0-431b-8f09-635464c89dc0" />






