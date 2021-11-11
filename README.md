# Welcome to the issues page for Bubbles!

# About this game
This is a project I started 9/22/21 and set a deadline of 9/27/21@00:00 (Wednesday-Sunday). This is the first time taking a game from concept to a working product (and also in such a short time frame). Yes, I made my own game engine, rendering code, and collision system for this game. I have, however, viewed examples extensively (mainly Vulkano for rendering and eGUI for the GUI).

# Bug reports/Feature requests
## How to submit a bug report
1. Create a new issue
2. Title the issue `[BUG] Short description here`. Please limit the description to less than 12 words
3. Describe the bug.
4. Describe how to reproduce the bug
5. Provide the logs (see the itch page for the log file location)
6. Submit the bug report

## How to submit a feature request
NOTE: Requested features may never get implemented since I am a full-time college freshman with a busy schedule.
1. Create a new issue
2. Title the issue `[FEATURE] Short description here`. Please limit the description to less than 12 words
3. Describe the feature. If I have any confusion about what something means, then I will comment a question in the issue.
4. Address any questions I have. If the questions are not addressed, I may get the implementation of the feature wrong.

## How to submit a question
NOTE: If a question is asked enough then I will put it in the FAQ.
Questions that are in the FAQ will get the `duplicate` tag and will be closed with the comment `See FAQ`
1. Create a new issue
2. Title the issue `[QUESTION] Short description here`. Please limit the description to less than 8 words
3. State your question clearly.
4. If the question is a duplicate, it will get a `duplicate` tag, a relevant question will be linked, and the question will be closed.

# FAQ
## Will macOS be supported?
I would say "No," but there may be a time in the far future where I will build for macOS.
As of 11/1/21 there is **NO SUPPORT** for macOS, and no support is planned either.
Please do not ask

## What font is that?
Regular text: Ubuntu-Light by [Dalton Maag](http://www.daltonmaag.com/) [License](https://ubuntu.com/legal/font-licence)
Mono text: [Hack-Regular](https://github.com/source-foundry/Hack) [License](https://github.com/source-foundry/Hack/blob/master/LICENSE.md)

## Why the name "bubbles?"
Because the objects you shoot at look like bubbles. Also, asteroids is kind of taken.

## How many sprites are in this game?
None! In fact, all of the entities are vector graphics hard-coded into the source. The asteroids are 8 triangles, the bullets are 1, and the ship is 4. The only images are the ones uploaded to the GPU for font rendering (rasterized TTF font data).

## Open source?
As of right now, no. This will not be open source.

### When will it be open source?
If you keep asking then never.

### Why not?
1. I spent a lot of time on this project and don't feel like the code is ready to be open source (it is really bad).
2. I may sell this game once it is in a much more polished state.
3. The codebase may be reused to power some of my future games. If not, open sourcing this code is much more likely to happen.
4. The original name was "Asteroids" which can be confusing. The name was changed because the objects look more like bubbles than asteroids.
5. Because I said so.
