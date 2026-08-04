# Sound Map recordings

Drop field recordings here, named with the location slug:

    riverside-park
    central-park
    lower-east-side
    lincoln-square
    west-village

Accepted extensions (checked in this order): .mp3, .m4a, .ogg, .wav

Example: assets/sound/central-park.mp3

The page auto-detects whichever file is present on load, reads its real
duration, and plays it looped. Any location without a file falls back to
the synthesized placeholder ambience.
