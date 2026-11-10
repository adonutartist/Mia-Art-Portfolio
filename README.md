# Miami's Portfolio Website

An art portfolio website showcasing Miami's artwork, creative projects, and commission info.

## Features

- **Home:** Introduction & social media links.
- **About:** Artist intro, background, and tools.
- **Gallery:** Collection of artwork.
- **Journal:** Individual journal entries with automatically generated previews, sorted by date.
- **Commissions:** Commission prices, examples, and Terms of Service.
- **Links:** Social media, other platforms, and guestbook.
- **Compatibility:** Can run on both mobile and PC, has a set of css code that makes it viewable on mobile without any orientation disperancies.
- **Guestbook:** Made using atabook u can leave messages anonymously for miami to read later or rpely back, also has auto moderation to ban any slangs and bad words :D
- **Image slider:** Made a image sliding thing on comms page for more interactive viewing :p

## Languages & Tools Used

- HTML
- CSS
- JavaScript
- Google Fonts
- Atabook
- Vercel

## Screenshots

### Home
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/50467006-0b3e-499c-ace2-01a08cb7b00d" />

### About
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7155896c-1c0f-4856-8cc4-6be565ae96fd" />

### Gallery
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/143904cb-6308-4f3e-b0f0-f55afa00f9f2" />

### Journal
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/180b6701-814e-483b-be52-4a42d966a3de" />
<img width="1913" height="714" alt="image" src="https://github.com/user-attachments/assets/a37b5328-cadd-4bb5-9896-cc6646980243" />

### Commissions
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/df1aaaee-5bd9-4543-8819-0b7cff4f490c" />

### Links
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b88997c-4de2-4e1f-9c24-5c76c55d8a95" />

## Project Structure

```text
portfolio/
├── index.html
├── about.html
├── gallery.html
├── blog.html
├── commissions.html
├── links.html
├── style.css
├── assets/
├── artgallery/
├── blogposts/
└── commissions/
```

## Journal System

Each journal entry is stored as a separate HTML file inside `blogposts/`.

The main Journal page retrieves each entry's title, date, description, and cover image from its metadata and automatically displays previews in chronological order.

To add an entry:
1. Duplicate `journal-template.html`.
2. Edit its metadata and content.
3. Add its filename to the `journalFiles` array in `blog.html`.

## Demo Link

https://miamiartz.vercel.app/index.html

---

**Developer:** Nemo  
**Portfolio Owner:** Miami

---

<div align="center">
<img width="300" alt="nemo" src="https://github.com/user-attachments/assets/07afdbb5-4254-42f4-82ae-558077fdc3c6" />
</div>
