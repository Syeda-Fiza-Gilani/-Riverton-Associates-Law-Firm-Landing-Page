# ⚖️ Riverton & Associates: Law Firm Landing Page

A responsive landing page for a fictional law firm, built with **React** and **Vite**. I made this to practice turning a UI design into working code, matching the layout, spacing, typography and colors as closely as I could.

<img width="1561" height="798" alt="image" src="https://github.com/user-attachments/assets/2326228f-f144-43ae-a369-e89c30fb444e" />

---

## ✨ Features

- Sticky navigation bar with smooth scrolling to each section
- Hero section with a call-to-action button
- Practice areas grid (Family Law, Business Law, Criminal Defense, Personal Injury, Real Estate)
- About section with the firm's key values
- Stats band (years of experience, cases handled, satisfaction rate)
- Testimonials section with clickable slider dots
- Contact form with a practice area dropdown
- Responsive layout for desktop, tablet and mobile

## 🛠️ Built With

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Lucide React](https://lucide.dev/) for icons
- Plain CSS with CSS variables
- Google Fonts: Newsreader and Manrope

## 🚀 Getting Started

Make sure you have [Node.js](https://nodejs.org/) installed, then:

```bash
# clone the repo
git clone https://github.com/Syeda-Fiza-Gilani/riverton-law.git

# go into the folder
cd riverton-law

# install dependencies
npm install

# start the dev server
npm run dev
```

Then open the local URL shown in your terminal (usually `http://localhost:5173`).

To create a production build:

```bash
npm run build
```

## 📁 Project Structure

```
riverton-law/
├── public/
│   └── images/        # hero, about, contact background, avatars
├── src/
│   ├── App.jsx        # all page sections
│   ├── index.css      # styles and design tokens
│   └── main.jsx       # entry point
├── index.html
└── package.json
```

## 🎨 Design Notes

- **Colors:** navy `#111c2b`, gold `#c8a46a`, cream `#faf8f4`
- **Fonts:** Newsreader for headings, Manrope for body text
- The page is built from the UI mockup, so most of the work went into getting spacing and sizing right

## 📚 What I Learned

- Building a layout with CSS Grid and Flexbox
- Making a page responsive with media queries
- Organizing page data (like practice areas and reviews) into arrays and rendering them with `.map()`
- Handling small interactions with the `useState` hook
- How much small design details matter

## 🔮 Future Improvements

- Connect the contact form to a backend or email service
- Add a mobile hamburger menu
- Build the "Our Team" and "About" pages
- Add scroll animations

## 🙋 About Me

I'm a student learning AI-Native Full Stack development. Feedback and suggestions are welcome!

- GitHub: [@your-username](https://github.com/Syeda-Fiza-Gilani)
- LinkedIn: [your-name](https://linkedin.com/in/www.linkedin.com/in/syeda-fiza-gilani-9081aa41b)

---

*This is a practice project.*
