# _Website for a band_

[View Project Here](#)

This is a website for a group named Oompah Brass. They are a five piece brass group whose varied gigs include regular residences, large oktoberfest events, weddings and corporate functions. Their show, which generally includes upbeat pop covers, is upbeat, energetic and fun, and I want to build a website that represents this. 

## User Experience (UX)

### Visitor goals

  - I anticipate two different users for the website. Firstly, the perspective client who is looking to hire the band, and secondly, the follower, who is a fan of the band and looking to see when they are next playing.
  - A first-time visitor should find this website clean, clear and concise offering a great first impression of the band.
  - All visitors should navigate easily between the pages using the navigation bar and integrated buttons. 
  - Perspective clients will be able to find out about the band, see and hear examples of their work and enquire about booking them.
  - Followers of the band will be able to find a list of upcoming gigs they are able to go and watch and follow links to the band's social media pages from any page on the site. 

### Project goals

  - The client wants a website that represents the bands fun and energetic but professional brand. 
  - The website will display examples of the band's work through videos, photos and tracks. 
  - The client would like the website to be user friendly and easy for the site user to make an enquiry or book the band. 
  - The site should display upcoming gigs as well as display media content to help advertise the band's product.

## Design

  - Color Scheme
    The main colors are the bands two signature colors; black and bright pink. I will also you some whites for text to contrast a black background. 

  - Typography 
    The two fonts used are Raleway and Roboto Slab, both with a fallback option of sans-serif. Raleway is used for the quotes on each page while Roboto Slab is used for the bulk of the other text. 

  - Imagery
    Imagery is an important part of the website as it portrays the energy of the abdn at various gigs they have performed at. The home image is simple and clear of a background to emphasise the cleanliness of the page and not to detract from the two action buttons. On various other pages, fun imagery will be used at the top of the page as well as a gallery section on the media page. 

  - Overall, the website is fairly simple in design with important funcitonal aspects easy to find and carry out, i.e. watch a promotional video of the band or contact with an enquiry. Each page has a specific function and is not too overcrowded. 



## Testing

### Lighthouse

After using the Lighthouse feature in Chrome DevTools I made the following changes.
  - I added a meta description to the <head> section of each page to summarise the page for the benefit of search engines. 
  - I added text to the social media icons for screen readers. 
  - I added rel="noopener" to all external links to ensure I don't expose the site to performance or security issues. 
  - On the About Us page, my links initially said 'Click here' and I changed them to more descriptive text, clearly stating the destination of the links. 
  - On the Media page, I added titles to the YouTube and Soundcloud windows. 
  - On the Contact page, I added labels to the form that were only visable for screen readers. 

Overall, this helped improve the performance, accessibility, best practices and SEO scores, the results of which are below.

### Index 
![Performance:93 Accessibility:91 Best Practices:100 SEO:100](images/readme/lh-index.png)

### About Us
![Performance:97 Accessibility:96 Best Practices:100 SEO:100](images/readme/lh-aboutus.png)

### Media
![Performance:70 Accessibility:93 Best Practices:100 SEO:100](images/readme/lh-media.png)

### Gigs
![Performance:95 Accessibility:88 Best Practices:100 SEO:90](images/readme/lh-gigs.png)

### Contact
![Performance:95 Accessibility:91 Best Practices:100 SEO:100](images/readme/lh-contact.png)





changes/bugs:
Index page:
changed bg color of index as solid black was too flat. Slightly, off-black made imgs stand out more.
social icons were too lrg for phone view - added media query. 
nav bar toggler not displaying menu when clicked - hadn't added the jQuery tags at the bottom of the page
white section appearing down RHS of page - clear padding and margin on .row and remove font weight change to buttons. Also, changed homep page buttons to just links. 
Changed Nav bar location and added logo to nav bar. Kept Nav items to the left as didnt look right when centered and having logo on left. 
photo icons was displaying above fixed nav bar - changed z-index to 100.
As index.html doesnt have a page heading, the picture was disappearing. In order to keep using grouped css, i just added some inline styling. 
Changed the format of the contact page to include a form.
Contact page textarea was adjustable and leaving a white section at the bottom of page - changed in css to fixed area. 