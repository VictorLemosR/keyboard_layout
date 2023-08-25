# Layout change for keyboard

The change on layout is made via [kanata](https://github.com/jtroo/kanata).
Although there are a few options to do that, kanata is specially useful for the
addition of extra layers ![image of layout and layers](/keyboard.png)

After analyzing some layouts, my 2 favorites were:
[colemak-dh](https://colemakmods.github.io/mod-dh/) and [hands down
neu](https://sites.google.com/alanreiser.com/handsdown/home/hands-down-neu)
Colemak-dh was chosen, but many tweaks were made to suit my needs (writing in
portuguese, english and programming)

The decision process was mainly based on score from [layout
analyzer](https://stevep99.github.io/keyboard-layout-analyzer/#/main)
Adjustments were made focused on reducing overall SFB (same finger bigram), 
pinky usage, pinky distance, pinky SFB

The text used to test the layouts is in 'Keyboards\Texts for analyzer'

# Installation for windows

1. Download [binary](https://github.com/jtroo/kanata/releases)
2. Use conhost in task scheduler 
'C:\Windows\System32\conhost.exe --headless C:\kanata\kanata.exe --cfg
   C:\kanata\kanata.kbd'
[link](https://github.com/jtroo/kanata/discussions/193#discussioncomment-5276656)
