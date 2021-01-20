# Power Bottom

A Powercord plugin for [bottom](https://github.com/kaylynn234/bottom).

Perhaps you have found yourself in this situation before:

![,,,,,,,,,](https://cdn.discordapp.com/attachments/644479051918082050/799905088541425664/bottom.jpg)

The divine Powercord plugin exists to alleviate this pain. No longer will you struggle when communicating with the average Discord user.

## But what does it actually do?

``bottom`` encodes UTF-8 text into a sequence comprised of bottom emoji (`🫂✨🥺❤️`, with ``,`` sprinkled in for good measure) followed by `👉👈`.
It can encode any valid UTF-8 - being a bottom transcends language, after all - and decode back into UTF-8.

For example, the ubiquitous `Hello world!` becomes
```
💖✨✨,,👉👈💖💖,👉👈💖💖🥺,,,👉👈💖💖🥺,,,👉👈💖💖✨,👉👈
✨✨✨,,👉👈💖💖✨🥺,,,,👉👈💖💖✨,👉👈💖💖✨,,,,👉👈
💖💖🥺,,,👉👈💖💖👉👈✨✨✨,,,👉👈
```
`がんばれ` becomes
```
🫂✨✨🥺,,👉👈💖💖✨✨🥺,,,,👉👈💖💖✨✨✨✨👉👈🫂✨✨🥺,,👉👈
💖💖✨✨✨👉👈💖💖✨✨✨✨🥺,,👉👈🫂✨✨🥺,,👉👈💖💖✨✨🥺,,,,👉👈
💖💖💖✨✨🥺,👉👈🫂✨✨🥺,,👉👈💖💖✨✨✨👉👈💖💖✨✨✨✨👉👈
```
(both wrapped across lines for your convenience)

As you can see, using `bottom` to encode text is extremely space-efficient, and is the ideal encoding approach for all situations.
