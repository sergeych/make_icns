# make_icns .png to .icns converter script

Intended to run on MacOSX.

I was always sick of creating .icns icons for MacOSX desitributions manually, so I have finally written the bash
scipt to do it automatically.

All you need is a big square .png as source, should ve 1024 by 1024 or bigger. Then jusy call it as 

```
make_icns <some_file>.png
```

And you'll get <some_file>.icns.

It will not work on linux unless you'll provide `sips` and `iconutil` from mac. Or add some code to use, say, convert and whatever else instead of iconutil. Leave me a PR then :)

