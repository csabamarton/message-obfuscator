# 🛡️ Message Obfuscator (by RelationRhythm)

A lightweight, privacy-focused tool to anonymize your exported chat files — runs 100% in your browser, no installs, no tracking.

---

## What it does

This tool takes your exported chat (e.g. from WhatsApp) and replaces names and messages with anonymous labels, like this:

```
Original:
01/01/25, 14:52 - Anna: Hey, how are you?

Obfuscated:
01/01/25, 14:52 - User1: TEXT(18)
```

It keeps the *structure* of the conversation — like timestamps, message types, and approximate message lengths — but removes any personal or sensitive content.

---

## How to use it

1. Download the `index.html` file from this repository
2. Open it in any browser — desktop or mobile
3. Tap to select your exported `.txt` file
4. Click **Obfuscate**
5. View or download the cleaned-up version

> ✅ No internet needed — works fully offline  
> 🧪 Tested on WhatsApp `.txt` exports

---

## Why this exists

This tool was built as part of [RelationRhythm](https://relationrhythm.com), a project exploring how we communicate — without reading what we say.

We wanted something that:

- Works without installation
- Doesn’t upload private data anywhere
- Can be shared and used by anyone, easily

It’s ideal for researchers, designers, or anyone curious about their own digital habits — without compromising privacy.

---

## Try it online

You can also use the browser version here:  
🔗 [csabamarton.github.io/message-obfuscator](https://csabamarton.github.io/message-obfuscator)

Just open it and you're ready to go.

---

## How it works (in short)

- Recognizes WhatsApp-style timestamps and names
- Gives each user a label like `User1`, `User2`, etc.
- Replaces the message with a simple label:
  - `TEXT(120)` → for regular messages
  - `MEDIA` → for images, videos, etc.
  - `AUDIO` or `DOCUMENT` → based on hints in the file

---

## Tech stack

- HTML + CSS + JS
- Fully self-contained (no dependencies)
- Works offline and mobile-friendly

---

## License

MIT – feel free to fork, remix, and share.

---

Made with care by [Csaba Marton](https://relationrhythm.com)
