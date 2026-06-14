# Trackbox BOM

This BOM is intended for friend/tester self-builds of Trackbox. It reflects currently tested parts plus a few specced-but-untested audio components.

## Notes

- **Raspberry Pi 5 (4GB)** is the currently tested core platform.
- Given current Pi 5 pricing, it would be useful to test **Pi 3** and **Pi 4** compatibility for lower-cost builds.
- If using **two Anker card readers**, they are too wide to fit side-by-side in the Raspberry Pi USB-A ports without a spacing adapter.
- Other card readers and adapters may work and may even be preferable if a lower-profile option is found. I can help support alternatives if they do not work out of the box.
- Items marked **Untested** are specced but have not yet been validated in a full Trackbox build.

## BOM

| Category | Part | Status | Notes | Vendor | Link |
|---|---|---|---|---|---|
| Core | Raspberry Pi 5 (4GB tested) | Tested | Current tested platform. Pi 3 / Pi 4 testing recommended for lower-cost builds. | Adafruit | https://www.adafruit.com/product/5812 |
| Display | Waveshare 2.8 inch 320x240 screen | Needs confirmation | Current display candidate. | Amazon | https://a.co/d/0bDNxgW6 |
| Storage / USB | Anker card reader | Needs confirmation | If using two, they are too wide to fit side-by-side directly on the Pi. | Amazon | https://a.co/d/0h34fN50 |
| Storage / USB | USB spacing adapter | Conditional | Needed if using two Anker card readers side-by-side. | Amazon | https://www.amazon.com/dp/B0BVH24NHM?th=1 |
| Audio Out | PCM5102A headphone out DAC | Untested | Specced but not yet validated. | Amazon | https://a.co/d/04uAqcG0 |
| Audio In | PCM1808 line-in ADC | Untested | Specced but not yet validated. | Amazon | https://www.amazon.com/dp/B0D9LNGBD1 |
| Speakers | DWEII speakers | Untested | Specced but not yet validated. | Amazon | https://www.amazon.com/dp/B0BWYBFPW8?th=1 |
| Speaker Amp | MAX98357A amp | Untested | Specced but not yet validated. | Amazon | https://www.amazon.com/dp/B0DPJRLMDJ |
