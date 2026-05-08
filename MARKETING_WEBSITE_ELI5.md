# ELI5: How to edit your marketing website

You do **not** need to code. Treat the website like a fill-in-the-blank document.

## 1. The only file you need most of the time

Open this file:

```text
static/index.html
```

That is your homepage.

## 2. Change the business name

1. Open `static/index.html`.
2. Press **Ctrl+F** on Windows or **Command+F** on Mac.
3. Search for:

```text
Your Name Studio
```

4. Replace it with your real business or personal brand name.

## 3. Change the big headline

Search for this sentence:

```text
Make your work look
```

Then replace the headline around it with what you want to say.

Simple formula:

```text
I help [type of person] get [good result] with [your service].
```

Example:

```text
I help beauty brands get more bookings with bold content and smart SEO.
```

## 4. Add your creative projects

Search for:

```text
Project name goes here
```

Replace the example project titles and descriptions with your real work.

For each project, write:

- What you made.
- Who it was for.
- What result happened.

Example:

```text
Instagram launch for a skincare brand. We created bright product visuals and 20 captions, helping the brand sell out its starter kits in 2 weeks.
```

## 5. Add your SEO keywords

Search near the top of `static/index.html` for:

```text
<meta name="keywords"
```

Replace the example keywords with words your customers might type into Google.

Example:

```text
SEO copywriter, beauty brand marketing, creative direction, content strategy, product launch copy
```

## 6. Change your services

Search for these example service names:

```text
Creative Direction
SEO Content
Marketing Systems
```

Replace them with the 3 main things people can pay you for.

Good service names are short and clear, like:

- Website Copy
- SEO Blog Posts
- Brand Photoshoot Direction
- Social Media Content
- Launch Strategy

## 7. Change contact details

Search for:

```text
hello@example.com
```

Replace it with your real email.

Search for:

```text
yourhandle
```

Replace it with your real Instagram or LinkedIn handle.

## 8. Preview it on your computer

From the project folder, run:

```bash
npm start
```

Then open this in your browser:

```text
http://localhost:8000
```

If something looks wrong, undo your last text change and try again.

## 9. Tiny SEO checklist before publishing

Make sure the page has:

- A clear title that says what you do.
- A simple first headline.
- Your city or country if clients search locally.
- Real project examples.
- Real service names.
- A real email or booking link.
- Words your clients would search on Google.

## 10. What not to touch

If you are nervous, avoid changing anything inside these areas unless you know what you are doing:

```text
<style>
...
</style>
```

That area controls colors, spacing, and design.
