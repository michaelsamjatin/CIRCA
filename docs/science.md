# Why red

## The short version

Your body clock does not mainly read light through the cones you see colour with. It relies on a small set of retinal cells, the intrinsically photosensitive retinal ganglion cells (ipRGCs), which contain the pigment melanopsin. Melanopsin is most sensitive to blue-cyan light around 480 nm and responds very little to long-wavelength red light. Evening light that excites melanopsin suppresses melatonin and pushes the clock later.

## Why "warm" filters are not enough

Night Shift and similar filters lower the blue channel but keep a lot of green. Melanopsin's sensitivity extends well into the green, so a warm-looking screen can still deliver a meaningful melanopic dose. Circa sets the green and blue output curves to zero, so the display only emits its red primary, which on typical LCD and OLED panels sits above about 600 nm, where melanopsin responds weakly.

## Brightness matters too

Dose depends on intensity as well as spectrum. Circa's intensity slider scales the red channel, so you can dim the screen at the same time. Use the lowest level that is comfortable to read.

## Full effect without the eye strain

Pure red at full brightness is hard to work with: white pages glare, and dark grey text sinks into black because only one colour channel is left to carry contrast. The Readable preset keeps green and blue fully off, so the spectral effect is the same, and changes three things for comfort:

- **Dark Mode.** Red text on a black background emits far less light in total than black text on a bright red page. Less light is better for your body clock and easier on the eyes in a dark room.
- **Clarity.** The red curve is bent so dark greys get brighter while black stays black and the brightest value stays where it is. Anti-aliased text and subtle interface lines stay visible.
- **Capped intensity.** The red channel peaks at 70%, which avoids glare without making text dim.

## The spectrum controls and the body-clock estimate

A screen makes every colour from three primaries: blue (about 460 nm), green (about 530 nm) and red (about 620 nm). Circa sets each one separately. The Amber preset lets some green back in for a warmer, more natural look; every other preset keeps green and blue off because melanopsin responds strongly to both.

The "Body-clock light" figure is a rough estimate of the melanopic light of a white screen in the current style, compared with a normal white screen. For a typical sRGB display, each primary's share of melanopic light is its share of luminance (red 21 %, green 72 %, blue 7 %) times its melanopic-to-photopic ratio under CIE S 026, treating the primaries as narrowband. That gives blue about 66 %, green about 33 % and red about 0.5 %. Each primary's output is then scaled by its level raised to the display gamma of 2.2. Real panels have broader primaries, so treat the figure as an order of magnitude, not a measurement. Dark Mode and dark content lower the real figure further.

## What Circa does not do

- It is not a medical device and makes no clinical claim.
- It only changes your screen. Room lighting usually contributes far more evening light than a laptop does. Dim lamps and avoid bright overhead light too.
- Display red primaries differ between panels, and some emit a little light below 600 nm. Red mode reduces melanopic light greatly; it does not remove it entirely.

## Sources

1. Berson, D. M., Dunn, F. A., & Takao, M. (2002). Phototransduction by retinal ganglion cells that set the circadian clock. *Science*, 295(5557), 1070–1073.
2. Brainard, G. C., et al. (2001). Action spectrum for melatonin regulation in humans: evidence for a novel circadian photoreceptor. *Journal of Neuroscience*, 21(16), 6405–6412.
3. Lucas, R. J., et al. (2014). Measuring and using light in the melanopsin age. *Trends in Neurosciences*, 37(1), 1–9.
4. CIE S 026/E:2018. *CIE System for Metrology of Optical Radiation for ipRGC-Influenced Responses to Light.* International Commission on Illumination.
5. Brown, T. M., et al. (2022). Recommendations for daytime, evening, and nighttime indoor light exposure to best support physiology, sleep, and wakefulness in healthy adults. *PLOS Biology*, 20(3), e3001571.
