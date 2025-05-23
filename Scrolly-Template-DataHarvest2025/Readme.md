# DIY Scrolly Template – Instructions

## Chapter 1: How This Template Came to Be

This template was originally created for educational purposes by **Jonathan Soma**, professor at the Journalism School of Columbia University, New York.  
You can find this and other similar templates here:  
👉 https://github.com/jsoma/page-templates/

The template was later **updated by Dafni Karavola**, data journalist at Reporters United (Athens) and graduate of the Lede Program for Data Journalism at Columbia. The update was made during the investigation on Greece's largest tourist complex, **Costa Navarino**, led by **Myrto Boutsi** & **Dafni Karavola**, and published by **Reporters United** with the support of **Journalismfund Europe**.

📰 The investigation, part of the journalistic project _“No Man's Land: Digging for Water,”_ was published in three parts:

- **Part 1:** Water overconsumption at the expense of local resources and communities  
  👉 https://www.reportersunited.gr/13681/amilito-nero-costa-navarino/

- **Part 2:** Shrinking a Natura 2000 area to exclude Costa Navarino's hotels  
  👉 https://www.reportersunited.gr/15653/natura-costa-navarino/

- **Part 3:** Encroachment of the hotel’s restaurant on a protected beach and wildlife habitat  
  👉 https://www.reportersunited.gr/15438/costa-navarino-3-barbouni/

This version of the template was further adapted for the **DataHarvest 2025 workshop** on vertical storytelling.

It is a **DIY (Do-It-Yourself)** template—designed by a journalist for journalists. It requires little coding skills and is ideal for media organizations that cannot afford in-house developers.

You’re free to use and share this template. **Credit is appreciated.**

---

## Chapter 2: How the Template Works

### 🧠 Understanding the Logic

This template is built for **static images that change on scroll**.  
Each image is paired with a text box that can contain:

- text
- images
- videos (from your computer or the internet)
- embedded social media posts
- interactive charts (e.g., Flourish, Datawrapper)
- basically anything you can put in an `<iframe>`

Each step of the template demonstrates some of these possibilities.

---

### 📁 The Template Includes:

- **`index.html`**  
  Contains the structure of the page and the scroll logic.  
  You’ll add your text content here.  
  At the bottom is a small JavaScript snippet. You only need to **adjust the image file type** (`.jpg`, `.png`, `.webp`). This line is **clearly flagged** in the HTML, and otherwise, you don’t need to touch the JavaScript.

- **`scrolly-styles.css`**  
  This file controls the design: font, color, layout, etc.  
  It is linked in the HTML and you can tweak it for custom looks.

- **Two sets of images**  
  One for **desktop** (landscape) and one for **mobile** (portrait).  
  Each image must follow this naming convention:  
  `image1-desktop.jpg`, `image1-mobile.jpg`  
  (`image[number]-[desktop/mobile].[extension]`)  
  Again, don’t forget to match the file extension in the JavaScript.

- **Any extra files** (images, videos, etc.) you reference in the text blocks.

---

## Chapter 3: How to Publish Your Scrolly

You’ll need to **host the template as a webpage**. There are two main options:

### Option 1: Use Your Media’s Website  
If your organization can host custom HTML, upload the template there.

### Option 2: Use GitHub Pages + Iframe  
This is easier and free. Upload your project to GitHub, then embed the scrolly on any article page using an iframe.

📹 **Tutorials to Get Started:**

- [Intro to GitHub](https://www.youtube.com/watch?v=YERMVqFvTB4)
- [Create a GitHub Pages Site](https://www.youtube.com/watch?v=5XhxR9Vs6zc)

---

## Chapter 4: Resources, Tips & Tricks

✅ **Best Practices:**
- Keep image files **under 1MB** for faster loading
- Use [Visual Studio Code](https://code.visualstudio.com/) with the **GoLive extension** to preview changes live
- Keep text **short and impactful**—this is a visual-first format
- Be creative with background images: use maps, charts, photos, or illustrations

🖼️ **Inspiration:**
- [Forever Pollution – The Cost of Remediation](https://foreverpollution.eu/lobbying/the-cost-of-remediation/) _(uses illustration)_
- [Auctions & Homes](https://dafnikaravola.github.io/auctions/) _(uses an annotated map)_

---

### ✨ Final Notes

This is a minimalist scrollytelling starter kit for journalists with little or no coding background. If you use it, share it, and improve it—we’d love to see what you create.

📝 Created by Dafni Karavola, dafni.karavola@gmail.com 
