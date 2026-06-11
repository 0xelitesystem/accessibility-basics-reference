# Images, structure, and forms

Three more basics cover much of the rest of everyday accessibility: describing images so people who cannot see them still get the information, structuring the page with real headings and landmarks so assistive technology can navigate it, and labelling form fields so people know what each one is for. These are the things screen reader users most often find broken.

## Alt text for images

Images need a text alternative, the alt attribute, that conveys what the image communicates, because a screen reader reads that text to someone who cannot see the image. What the alt text should say depends on the image's purpose. An image that carries information, a chart, a photo that matters, a logo, needs alt text describing what it conveys. An image that is purely decorative, adding nothing beyond visual flourish, should have empty alt text so the screen reader skips it rather than announcing a meaningless filename. The mistake to avoid is leaving alt text off entirely, which often makes the screen reader read the filename, or writing useless alt like the word image. Good alt text answers what a sighted person would get from the image.

## Headings and structure

Screen reader users navigate a page largely by its structure, jumping between headings to find what they want, so a clear, correct heading structure matters as much for them as visual hierarchy does for sighted readers. Headings should be real heading elements in a logical order, one main heading for the page and nested subheadings below, not text that merely looks big. When headings are used for their meaning rather than their appearance, assistive technology can present an outline of the page that people use to navigate. Likewise, using the page's structural regions, the main content, navigation, and so on, as real landmarks lets screen reader users jump straight to the part they want. Structure that is only visual, with no real underlying markup, leaves these users with no way to navigate.

## Labelled form fields

Every form field needs a label that is programmatically connected to it, so that a screen reader announces what the field is for when the person reaches it. A text box with only a visual placeholder, or a label that merely sits near it without being linked, leaves a screen reader user not knowing what to type. Real labels, properly associated with their fields, fix this and also make the visible label clickable, which helps everyone. Forms are where labelling failures hurt most, because a person who cannot tell which field is which cannot complete the form, and forms are often exactly where the important actions live, like signing up or buying.

## Error messages and instructions

Forms also need to communicate errors and requirements in ways everyone can perceive. As the text-and-color page noted, an error shown only by a red border fails people who cannot see the color, so errors need text that says what is wrong and, ideally, how to fix it, connected to the field so assistive technology conveys it. Instructions and required-field markers should likewise be text, not color or position alone. The goal is that a person filling out the form by keyboard and screen reader gets the same guidance a sighted mouse user does: what each field is, what is required, and what went wrong.

## These cover the common screen reader failures

Alt text, real heading and landmark structure, and properly labelled forms with perceivable errors together address the barriers screen reader users hit most often. They are not exotic; they come almost for free when you build with real, meaningful markup, describe your images, and label your controls. The recurring theme is using elements for their meaning rather than only their appearance, because assistive technology reads the meaning. A page built that way is navigable and usable by screen reader; a page built only for visual appearance, with structure faked through styling, usually is not.
