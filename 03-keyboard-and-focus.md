# Keyboard and focus

Many people do not use a mouse. People with motor disabilities, people using screen readers, and people who simply prefer it navigate with a keyboard, moving through a page with the Tab key and activating things with Enter or Space. If something on your site can only be done with a mouse, those people cannot do it. Keyboard access is one of the most important and most commonly broken parts of accessibility.

## Everything must be reachable and usable by keyboard

The core requirement is that every interactive thing, every link, button, form field, menu, and control, can be reached and operated with the keyboard alone. A person should be able to Tab to it and activate it without ever touching a mouse. This usually works automatically when you use real interactive elements, native links and buttons and form controls, because the browser makes those keyboard-operable by default. It breaks when interactivity is bolted onto elements that are not naturally interactive, like making a plain element clickable with script but not keyboard-operable. Using the real elements for the job is most of how you get keyboard access for free.

## Focus must be visible

As a person Tabs through a page, the element currently in focus needs a visible indicator, usually an outline, so they can see where they are. Browsers show a focus outline by default, and a common mistake is removing it for looks without replacing it, which leaves keyboard users unable to tell what is focused. If you do not like the default outline, replace it with a clear visible style of your own; do not simply remove it. A keyboard user with no visible focus is navigating blind, which makes the page effectively unusable for them even if everything is technically reachable.

## Focus order should make sense

The order in which focus moves through the page as a person Tabs should follow the logical reading order, generally top to bottom and left to right, matching how the content is meant to be read. When the focus order jumps around unpredictably, because the source order does not match the visual order, keyboard users get lost. Keeping the underlying source order aligned with the visual and logical order keeps the focus order sensible. This is mostly a matter of building the page in a logical order rather than rearranging it purely visually in ways that leave the real order scrambled.

## Do not trap focus

Focus should never get stuck somewhere a keyboard user cannot escape. A common version is a popup or overlay that traps focus inside it with no keyboard way out, or that, worse, cannot be reached or closed by keyboard at all. Interactive overlays need to be operable and dismissable by keyboard, returning focus sensibly when closed. A keyboard trap can strand a user on a page entirely, which is among the more severe accessibility failures because it can make the whole site unusable from that point.

## The keyboard test

The single most valuable accessibility test you can do yourself costs nothing: put the mouse aside and try to use your site with only the keyboard. Tab through it. Can you reach every link, button, and field? Can you see where focus is at every step? Can you activate everything and complete the main tasks? Can you open and close any menus and overlays? If you get stuck, cannot see the focus, or cannot reach something, you have found a real barrier that keyboard and screen reader users hit. This one test, done honestly, surfaces a large share of the operability problems on most sites.
