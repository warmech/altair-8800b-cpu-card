# Altair 8800B CPU Card
This is a reproduction of the MITS Altair 8800B CPU card, with some cleanup to trace routing and pad placement. While there are reproductions of the 8800's CPU card available, the 8800B's CPU card has not (to date) been reproduced. You may be wondering why this version of the Altair's CPU card exists and the original 8800 card is not useable; this is because the architecture of the 8800 and 8800B differ ever so slightly, making each computer's CPU card incompatible with the other without making some hardware changes.

This version of the card incorporates all of the pertinent hardware design of the original 8800B card, but leaves out all of the unnecessary and/or ancillary traces and pads that were placed for potential future development. Orphaned pads, jumpers, and vias have been removed and only two unlabeled jumpers remain in the vicinity of IC "T" near the bottom-left side of the PCB. The goal of this project was not to recreate the card in a 1:1 fashion, as the original PCB was replete with elements that served no discernably meaningful purpose. Instead, this revision offers a nice, clean, annotated PCB for those whose 8800Bs are either missing a CPU card (as mine was) or whose CPU cards are damaged beyond repair.

This design is presently untested and I am awaiting a set to be fabricated. Once I have tested this card in my 8800B, I will update this disclaimer to indicate as much.

![Altair 8800B CPU Front](/images/renders/pcb_front_angle_render.png)
