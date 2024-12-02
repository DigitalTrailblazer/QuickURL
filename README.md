# QuickURL - URL Shortener 🖇️  

QuickURL is a lightweight URL shortener application that simplifies long URLs into short, shareable links. With a clean UI and robust backend, it tracks shortened URLs and their click counts while ensuring a seamless user experience across devices.

---

## Features 🚀  
- **URL Shortening**: Instantly transform lengthy URLs into concise links.  
- **Redirect Functionality**: Shortened links redirect users to the original URL.  
- **History Tracking**: View previously shortened URLs.  
- **Click Count**: Track the usage of each link.  
- **Responsive Design**: Fully functional on desktops and mobile devices.  
- **Modern Animations**: Smooth animations powered by GSAP.  

---

## Tech Stack 🛠️  

### Frontend:  
- **EJS** for templating  
- **CSS** for styling and responsiveness (includes GSAP for animations)  

### Backend:  
- **Node.js** and **Express.js** for server-side functionality  
- **shortid** for unique URL generation  

### Database:  
- **MongoDB** for storing URLs and click count  

---
## Usage ✨
Shorten a URL: Enter a long URL in the input field and click on "Short URL". The shortened link will be displayed and stored in history.

Access Original URL: Use the shortened link to redirect to the original URL.

---

## Installation 🏗️  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/DigitalTrailblazer/QuickURL.git  
