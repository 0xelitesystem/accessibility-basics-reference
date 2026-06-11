# Text and color

A large share of accessibility problems are about whether people can read what is on the screen. Three basics cover most of it: enough contrast between text and its background, never using color as the only way to convey something, and using real text that people can resize. Each addresses a common, concrete barrier for people with low vision or color vision differences.

## Contrast

Text needs enough contrast against its background to be readable by people with low vision, and the standard puts numbers on this. The WCAG AA threshold is a contrast ratio of at least 4.5 to 1 for normal text and 3 to 1 for large text, where large means roughly 24px and up, or 18.66px and up if bold. Light gray text on a white background, a common design choice, often fails this and is hard for many people to read. The color-contrast-checker in this portfolio measures any text-and-background pair against these thresholds. Checking your body text, your links, and your buttons against the background they sit on catches one of the most frequent accessibility failures.

## Do not rely on color alone

Color should never be the only thing carrying meaning, because people with color vision differences may not distinguish it, and assistive technology does not convey it. A form that marks errors only by turning fields red, a chart that distinguishes lines only by color, a link shown only by a different color with no underline, each fails the person who cannot tell the colors apart. The fix is to pair color with something else: an error icon and text alongside the red, labels or patterns on chart lines, an underline on links. Color can reinforce meaning, but something non-color must also carry it.

## Use real, resizable text

Text should be actual text, not an image of text, because real text can be read by screen readers, resized by people who need it larger, and reflowed to fit the screen. Text baked into an image is invisible to assistive technology and turns blurry when enlarged. Likewise, the page should let people zoom and increase text size without the layout breaking or content being cut off; many people run their browser at a larger text size, and a layout that only works at the default size fails them. Building with real text and flexible layouts that survive zoom handles this, and it is mostly a matter of not fighting the browser's own resizing.

## Readable by default

Beyond the specific rules, ordinary readability helps everyone, especially people with cognitive differences or low vision. Reasonable text size, enough line spacing, lines that are not too long, and good contrast make text easier for all readers, not only those with diagnosed needs. Accessibility and plain good typography overlap heavily here. A page that is comfortable to read for a tired person on a phone in bright light is usually also closer to accessible, because the underlying problem, text that is hard to perceive, is the same one.

## The quick checks

For text and color, three checks catch most problems. Run your text-and-background color pairs through a contrast checker and meet at least AA. Look for anywhere meaning is carried by color alone, and add a non-color signal. Confirm the text is real text, not images, and that zooming to a larger size does not break the layout or hide content. These three together address the bulk of the perceivability barriers people with low vision and color vision differences actually encounter.
