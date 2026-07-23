# keyboard

# Planning
30min (tracked with Lapse)
I have gone for a semi-custom 60% layout, which I think will work well for my needs. It is in a Mac-style layout (e.g., Command key and Option). You can find the sketch of the layout in the repo.

# Schematic
1:30min 
Finished with the schematic layout, I had some trouble figuring out how to best arrange them and needed to do some research to find out if the exact placement was important at this point. Turns out the final sizes are only relevant in the next set, so could have saved myself some time. Well, anyway, looking good, moving on to the actual PCB

# PCB
(4:40min tracked with Lapse)
The PCB is finally done. I can't believe it took this long. I had so many issues; the first was realising that the switch cutouts need to be placed in the correct order, as in the schematic. Of course, I only realised this after placing all of them. The next thing to go wrong was realising that I had added too many rows to the schematic, so that had to change. And finally, it turns out I assigned the rows and columns in the wrong order, so I couldn't draw the traces on the board, meaning back to the schematic. To be honest, there still is the issue of switches over my Raspberry Pi; I'm not sure if it will work, but I think/hope that if it doesn't, I can just ignore those and cover them up (they are extra switches), so let's see. But the good news is that it's finished.

# PCB part 2
(2 hours)
When you think something is finished but it isn't. In my original design, I had switches over top of the Pi; to be honest, I'm not sure if it would have been a problem, but I don't want to risk it. So I had to go and make changes to the schematic, and because I had already added all the tracks to the PCB and then moved switches about, that had to be redone. I mean, I'm glad I decided to do it; getting the PCB and finding that it doesn't work because of strange switch placement would have been so bad.

# Key switch research
(3.5 hours)
Yep, this was a rabbit hole if there ever was one. I knew a very little bit about the actual switches, just that there are three overall categories. So I really did spend 3 hours researching and comparing. Now I think I always knew I wanted linear switches; I have been typing on laptops my whole life, so I'm just so used to it. What really threw me was the sound: clicky, deep, silent, tappy, loud, medium or quiet. I pretty quickly found out I don't like the clicky to annoying and loud, then found some medium ones that were nice and deep and thought I had found the best ones. But when I thought about them being louder than my laptop, it just seemed too much (I need quiet to concentrate). So, abandoning everything, I started looking into silent switches, found out that silent doesn't really mean silent, just quieter and that even that varied a lot. After many sound tests and reading, I found the TTC Frozen V2 and the Outemu Peach V2. Those seem like the best ones for me; the TTCs are a little more expensive, but they are a lot nicer. I'm really not sure what the budget is, so if constrained, I will go for the Outemu; if not, then the TTC. Both are extremely quiet but still have a deeper sound signature and are not clacky. Well, that concluded my search, just have to find the rest of the components. 
