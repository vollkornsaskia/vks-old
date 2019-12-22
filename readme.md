# Wie erstelle ich einen neuen Rezeptpost?

	cd ~/nikola
	source bin/activate
	cd ~/vollkornsaskia
	nikola new_post -i <link to post.md>
	git pull
	nikola github_deploy
	https://vollkornsaskia.de bei Github wieder hinzufuegen

# Wenn ich es nur ausprobieren will:

	nikola auto --browser
	C-c

Anmerkung: Das ganze sollte vom Thinkpad aus passieren, weil:

1. Da alles installiert und initialisiert ist
2. Da der SSH-key passt
