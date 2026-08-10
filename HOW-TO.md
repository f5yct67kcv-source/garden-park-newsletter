# Garden Park Guest House — Newsletter Template

Everything you need is in one single file: **newsletter-template.html**

---

## Brand basis

The template follows your *Brand Identity Quick Guide (2019)*:

| | |
|---|---|
| Green | `#B0CB1F` — accents, buttons, rules |
| Gray | `#656A75` — captions and secondary text |
| Black | `#000000` — header and footer bands |
| White | `#FFFFFF` — background |
| Dark green | `#4F5802` — links on white (the brand green is too light to read as text) |
| Headings | Times LT Std, falling back to Georgia / Times New Roman |
| Body text | Gotham Book, falling back to Helvetica / Arial |

Gotham and Times LT Std are not installed on most recipients' computers, and
email cannot load fonts the way a website does. The template asks for them
first and falls back automatically — so it looks right for you and stays
readable for everyone else.

**Still missing: the official logo.** The header currently shows the name set
in Times italic. As soon as you have the logo as a PNG with a transparent
background (white or gold version, about 900 px wide), it can go in — the
instructions are written into the file, search for `LOGO`.

---

## Golden rule

Never edit the original. Always make a copy first.

1. Right-click `newsletter-template.html` → **Duplicate**
2. Rename the copy, e.g. `newsletter-2026-autumn.html`
3. Work only in the copy

That way the blank template stays intact for the next newsletter.

---

## Step 1 — Change the text

Open the copy with **TextEdit** (Mac) or **Notepad** (Windows).
Right-click the file → *Open With* → TextEdit / Notepad.

Search the document for this symbol: **✏️**

Every editable spot is marked with it, numbered 1 to 17, with a short note
saying what it is. Change only the text between the `>` and `<` signs.

Example — you see this:

```
<h1 ...>Autumn colours in the Cairngorms</h1>
```

You change it to:

```
<h1 ...>Spring is here at Garden Park</h1>
```

Nothing else. Don't touch the part starting with `style=`.

**To change a link:** find `href="https://..."` and replace the address inside
the quotation marks.

Save with Cmd+S (Mac) / Ctrl+S (Windows).

---

## Step 2 — Put the images in

In the file you will find these five placeholders:

| Placeholder | What it is | Recommended size |
|---|---|---|
| `LOGO` | your logo (optional, see note below) | 900 px wide, transparent PNG |
| `BILD-1` | large title image at the top | 1200 × 700 px |
| `BILD-2` | image in the middle section | 1000 × 620 px |
| `BILD-3` / `BILD-4` | the two small side-by-side images | 800 × 600 px |
| `SIGNATUR` | your finished signature graphic (house + awards + Butterfly Cottage) | 1200 px wide |

There are **two ways** to get your pictures in. Way B is easier.

### Way A — images hosted online (best quality, recommended)

Upload the pictures to your website (or ask your web person to do it), then
replace the placeholder with the full web address:

```
src="BILD-1"      →     src="https://www.garden-park.co.uk/images/autumn.jpg"
```

Keep the quotation marks.

### Way B — drop them in inside Thunderbird (easiest)

Do Step 3 first, and simply leave the placeholders as they are. In Thunderbird
you will see empty grey boxes where the images belong. Click a box, press
Delete, then drag your picture from Finder into that spot. Thunderbird attaches
the image to the email automatically.

> Note on the logo: the header currently shows the "GARDEN PARK / GUEST HOUSE /
> GRANTOWN-ON-SPEY" wording as text, in gold on dark green. That always displays
> correctly, even when a recipient blocks images. If you'd rather use the logo
> graphic, the instructions are written right there in the file (search for
> `LOGO`).

---

## Step 3 — Into Thunderbird

1. Double-click the HTML file. It opens in your browser (Safari, Chrome, Firefox)
   — this is your preview. Check everything reads well.
2. In the browser: **Cmd+A** (select all), then **Cmd+C** (copy).
   Windows: Ctrl+A, Ctrl+C.
3. In Thunderbird: **Write** a new message.
4. Click into the message body and press **Cmd+V** (Ctrl+V).
5. Fill in the subject line, add the recipients as **BCC** (see below), send.

---

## Important: use BCC

Put your own address in the **To** field and all subscribers in **BCC**.
This way no recipient can see anyone else's email address — which is both
polite and required under data protection rules.

In Thunderbird: click the small arrow next to "To" and choose "Bcc".

---

## Before you send — quick checklist

- [ ] Sent a test email to yourself first
- [ ] Opened the test on your phone as well
- [ ] All images visible
- [ ] All links clicking through to the right place
- [ ] Subject line filled in
- [ ] Recipients in **BCC**, not in To
- [ ] Unsubscribe note at the bottom still present (this is a legal requirement)

---

## Adding or removing sections

The file is built from blocks. Each one is fenced off with comments:

```
<!-- BLOCK A START -->
   ...
<!-- BLOCK A ENDE -->
```

- **Don't need a section?** Delete everything from `START` to `ENDE`, including
  both comment lines.
- **Need one more?** Copy the whole block from `START` to `ENDE` and paste it
  directly underneath. Then change the text and the image name (e.g. `BILD-5`).

Blocks available:
- **BLOCK A** — image with heading, text and a link
- **BLOCK B** — highlighted box, e.g. for a special offer
- **BLOCK C** — two images side by side with captions

---

## Tested and working in

Outlook (Windows and Mac), Gmail (web and app), Apple Mail, Thunderbird,
iPhone and Android. Layout adapts automatically on mobile: the two side-by-side
images stack underneath each other and the text gets larger.

---

## If something goes wrong

Just start again from a fresh copy of `newsletter-template.html`. The original
is never modified, so nothing is ever lost.
