# Microchip Pulse Monitor RS232 PIC16F84 Quick Start

*For more C sample code, see [www.MicrochipC.com](http://www.MicrochipC.com/).*

Here's the scenario: at University of Canterbury, New Zealand, they operate a hugely expensive X-ray crystallography machine. It was water cooled, and each run would take 24 hours and cost the client a lot. Unfortunately, as the story goes, there was a problem with the water supply controller, and it would periodically drop pressure and the machine would shut down. This means the run would have to be started again.

So, Mike Pearce designed a water-monitor. It would measure the flow, based on pulses from a flow meter. If the pulses dropped below a pre-determined threshold, it would log the date and time out to a serial port. They set up a PC with a serial program, and came back the next day to see exactly when the flow had dropped.

Mike tracked down the problem and had the system adapted to counter for the glitches, due to this nice piece of design work.

For other projects like this, see [more sample code on www.MicrochipC.com](http://www.microchipc.com/sourcecode/).

## More C Sample Code

For more sample code, see [www.MicrochipC.com](http://www.MicrochipC.com/).

> Do you have any enhancements to share with the community? We honour 98% of pull requests within a few days!