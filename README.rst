ay3_jsfxr
=========

Quick 'n' easy game sound effects generator for the AY-3-8910.

Derived from jsfxr, a port of sfxr: http://www.drpetter.se/project_sfxr.html to HTML5.

Based on sn_jsfxr (Tursi's SN76489/VGM fork of jsfxr), adapted to target
the General Instruments AY-3-8910 sound chip used in the MSX line of
computers, the NABU PC, and many others.

This version exports sound effects in the ayfx
(.afx) single effect format used by Shiru's AY FX Editor
(ayfxedit). The effects can be:

- played on real hardware or in an emulator with the ayfxplay Z80 player
  that ships with ayfxedit;
- loaded into ayfxedit for further editing, or combined into an effects
  bank (.afb) there.

Note that the browser preview is still the sfxr synthesizer, not an AY
emulation: on hardware, pitch and volume only update once per frame, so
fast sweeps come out steppier than the preview.

.. image:: screenshot.png

Links
-----

sn_jsfxr fork:         https://github.com/tursilion/jsfxr

Original jsfxr:        https://github.com/chr15m/jsfxr

DrPetter's sfxr:       https://www.drpetter.se/project_sfxr.html

ayfxedit + ayfxplay:   https://shiru.untergrund.net/software.shtml


Thanks
------

 riffwave.js: http://www.codebase.es/riffwave/

 jquery-ui:   http://jqueryui.com/

 ayfxedit:    Shiru (the .afx format and Z80 player)
