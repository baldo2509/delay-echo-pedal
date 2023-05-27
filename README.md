# Delay/Echo Pedal

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This is a collection of documentation, schematics and CAD files for a DIY guitar
delay/echo effects pedal that uses a [PT2399 digital echo processor IC](https://datasheet.lcsc.com/lcsc/1808031633_PTC-Princeton-Tech-PT2399-SN_C126407.pdf) as the main
delay line.

The circuit mimics the 'lo-fi' sound of vintage BBD based delay effects while using
modern, readily available components.

## Controls

* DELAY: Delay time between echoes (min: 10ms, max: 1s).<br>	   As delay time increases, echo fidelity and high frequency response decreases.
* FDBK: Amount of echo signal that gets fed back into the delay line;<br>	  This controls the amount of echoes (min: 1 echo, max; self-oscillation)
* MIX: Amount of echo signal that gets sent to the output (min: none, max: ~2x clean signal level);

## Credits

This circuit is mainly an adaptation of the ['Sea Urchin'](https://www.madbeanpedals.com/EP/downloads/delay/SeaUrchin2019.zip) schematic by [MadBeanPedals](https://www.madbeanpedals.com/index.html);

Some circuit fragments from the ['Degenerator'](https://www.madbeanpedals.com/projects/_folders/Delay/docs/Degenerator.zip) schematic also by MadBeanPedals;

Both schematics are not patented and freely available.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].