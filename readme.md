# Wie erstelle ich einen neuen Rezeptpost?

	cd ~/nikola
	source nikola/bin/activate
	cd ~/vollkornsaskia
	nikola new_post -i <link to post.md>
	nikola github_deploy

# Wenn ich es nur ausprobieren will:

	nikola auto --browser

Anmerkung: Das ganze sollte vom Thinkpad aus passieren, weil:

1. Da alles installiert und initialisiert ist
2. Da der SSH-key passt