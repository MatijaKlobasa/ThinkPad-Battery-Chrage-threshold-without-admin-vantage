ThinkPad Battery Chrage threshold without admin and Vantage

This "program" is the result of me not beeing to set a battery charge threshold on my new work issued ThinkPad but the winodows store is blocked by IT and im a only a standard
user. Don't get me wrong, i could make my account to have admin rights if i wanted to but to avoid any incidents, so i decided to work around it. Which is good since this is
how this batch "program" was born.

Turns out Lenovos battery threshold is managed by the Lenovo Power and battery driver which is then triggered or disabled by Lenovo Vantage. But the best part is it can be
triggered by other things, like the program ChargeThreshold.exe that Lenovo themself made.
I included this program in the zip but here is the link anyway: https://download.lenovo.com/pccbbs//thinkvantage_en/metroapps/Vantage/ChargeThreshold/ChargeThreshold.exe

This is great! The program runs simply with launchung it with a CMD window(it does not have to be elevated) in its directory and giving it a value to set the battery % at.

example: ChargeThreshold.exe 80 70

The problem: making a .bat file would be easy but my antivirus makes this not beeing an option. So thats when it hit me: build a shortcut to cmd.exe, launch it in its
directory and enter the desired values. In this directory there are different shortcuts and instructions on how to use it. I included some preset ones (current threshold lookup,
OFF, 90, 80, 70) and a script that you enter the values manualy. Some are quiet, some time out and some wait for the user to exit. Slovenian and english versions are available.

Compatibilty: ¯\_(ツ)_/¯ no idea what its compatible with. With my limited testing i assmue that everything from XX30 series ThinkPads upto the latest ThinkPad computers are
supported.

Tested and working on: X230, T530, T570, X280, P51, T16 gen1 Intel,


Use this tiny (800kB ish) program instead of Lenovos bloated vantage as you wish, share it, mod it, whatever just don't sell it.
