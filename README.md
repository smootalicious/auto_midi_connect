# auto_midi_connect

Automatically connect midi usb devices using ALSA (aconnect)

This is a fork of  https://github.com/stevelittlefish/auto_midi_connect modified to use with handhelds device running firmware utilizing Emulation Station such as 351ELEC, ArkOS, TheRA.

Scripts have been modified to place in a "ports" directory and run directly from the device.

Scripts could aslo could also work with a RetroPie installation.

For raspberry pi users please refer consider the original linked above.

- midi_connect.sh - automatically map every MIDI device onto every other MIDI device.
- midi_disconnect.sh - disconnects all mappings on all midi devices.
