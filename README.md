# contacteur
Convert a switch action (ON/OFF) into a timed action: ON ... x ms wait ... OFF

Not much to be said about this, good excuse to look at the blueprint functionality of Homeassistant

The automation created by the blueprint will be actionned by one of the defined switch when created and turned off Timer milliseconds later.

So

Switch ON
    Wait time milliseconds
Switch OFF

Multiple switches can be defined within the automation independently.
