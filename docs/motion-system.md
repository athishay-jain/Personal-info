# Athishay.dev Motion System

Version: 1.0

---

# Philosophy

Motion is not decoration.

Motion communicates hierarchy, interaction, continuity, and intent.

Every animation must answer one question:

"What information does this motion communicate?"

If the answer is "nothing",

remove it.

---

# Motion Principles

• Fast

• Purposeful

• Natural

• Consistent

• Calm

• Interruptible

• Accessible

---

# Emotional Goals

Visitors should never notice the animations.

They should notice how smooth the experience feels.

The website should feel:

Confident

Premium

Intentional

Effortless

---

# Motion Categories

Entrance

Exit

Hover

Focus

Press

Loading

Scroll

Navigation

Page Transition

Feedback

---

# Motion Hierarchy

Micro Motion

↓

Component Motion

↓

Section Motion

↓

Page Motion

↓

Application Motion

Every level should feel connected.

---

###########################################################
# TIMING TOKENS
###########################################################

Instant

0ms

Ultra Fast

100ms

Fast

150ms

Normal

200ms

Comfortable

300ms

Slow

500ms

Large Transition

700ms

Hero Sequence

1000ms

Maximum

1200ms

Never exceed 1200ms.

---

###########################################################
# EASING
###########################################################

Standard

ease-out

Default interaction.

Ease In Out

Page transitions.

Spring Soft

Cards.

Spring Medium

Buttons.

Linear

Progress indicators only.

Never use bounce.

Never use elastic.

---

###########################################################
# STAGGER
###########################################################

Children

60ms

Cards

80ms

Large Sections

120ms

Hero Text

150ms

Maximum

200ms

---

###########################################################
# HOVER
###########################################################

Cards

Translate Y

-4px

Scale

1.01

Shadow

Increase slightly

Duration

200ms

Cursor

Pointer

---

Buttons

Background

Fade

Scale

1.01

Arrow Icon

Translate X

4px

Duration

180ms

---

Images

Scale

1.03

Duration

400ms

Overflow Hidden

Yes

---

Navigation

Underline

Slide

Opacity

100%

Duration

180ms

---

###########################################################
# PRESS
###########################################################

Buttons

Scale

0.98

Duration

100ms

Cards

Scale

0.995

---

###########################################################
# FOCUS
###########################################################

Blue Focus Ring

Opacity

100%

Duration

120ms

Keyboard Friendly

Always Visible

---

###########################################################
# HERO
###########################################################

Sequence

Navigation

↓

Headline

↓

Description

↓

CTA

↓

Statistics

↓

Background Detail

Never animate everything together.

---

Headline

Fade

Move Up

16px

Duration

700ms

---

Description

Delay

120ms

Fade

Duration

600ms

---

Buttons

Delay

220ms

Fade

Scale

Duration

400ms

---

Statistics

Delay

320ms

Stagger

80ms

---

###########################################################
# SCROLL REVEALS
###########################################################

Every section enters once.

Never repeat.

Fade

Move

20px

Duration

500ms

Threshold

20%

---

Cards

Fade

Translate Y

24px

Stagger

80ms

---

Timeline

Reveal as scrolling.

Current node highlighted.

---

###########################################################
# PAGE TRANSITIONS
###########################################################

Cross Fade

Opacity

0 → 100

Duration

300ms

Content

Slide

8px

No dramatic transitions.

No page flip.

No zoom.

---

###########################################################
# MODALS
###########################################################

Overlay

Fade

200ms

Dialog

Scale

0.96 → 1

Fade

Duration

250ms

Exit

Reverse

---

###########################################################
# DRAWER
###########################################################

Mobile Menu

Slide Up

Fade

Duration

300ms

Overlay Blur

Small

---

###########################################################
# COMMAND PALETTE
###########################################################

Blur

Fade

Scale

Duration

180ms

Input Autofocus

Yes

---

###########################################################
# GALLERY
###########################################################

Image

Fade

Scale

1.03

Duration

300ms

Lightbox

Crossfade

Keyboard Support

Yes

Swipe Support

Yes

---

###########################################################
# COUNTERS
###########################################################

Count Up

One Time Only

Duration

1200ms

Never repeat.

---

###########################################################
# LOADING
###########################################################

Skeletons

Shimmer

Duration

1.4s

Infinite

Spinner

Only when absolutely necessary.

Prefer skeletons.

---

###########################################################
# SCROLL PROGRESS
###########################################################

Thin Bar

Top

2px

Primary Blue

Smooth

No bounce.

---

###########################################################
# PARALLAX
###########################################################

Allowed

Very Light

Hero Background

Maximum

10%

Never apply to text.

Never create motion sickness.

---

###########################################################
# CURSOR
###########################################################

Default Cursor

Use System Cursor.

Never replace.

Never use blob cursors.

Never use trailing effects.

---

###########################################################
# ACCESSIBILITY
###########################################################

Respect

prefers-reduced-motion

Disable

Hero Motion

Scroll Motion

Parallax

Counters

Keep

Opacity Changes

Focus Ring

Navigation

---

###########################################################
# PERFORMANCE
###########################################################

GPU Accelerated

Use

transform

opacity

Avoid

width

height

top

left

box-shadow animation

filter animation

---

###########################################################
# MOTION RULES
###########################################################

Never animate for decoration.

Never delay user interaction.

Never block scrolling.

Never autoplay videos.

Never animate every element.

Motion should disappear into the experience.

If users notice the animation before the content,

the animation has failed.

---

# Final Principle

Motion should make the interface feel alive,

not busy.

The user should remember the product,

not the animation.
