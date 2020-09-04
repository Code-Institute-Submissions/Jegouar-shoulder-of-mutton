<h1>The Shoulder of Mutton, Wantage</h1>

This project consists of an enhancement to a local pub's existing website. View the original site [here.](http://www.theshoulder.pub/)

The general purpose is to provide a more exciting visual appearance to the current one page site, which consists of a simple background image and plain text.

<h2>UX</h2>

Following discussions with the landlord it was decided that the existing text successfully conveyed the desired information about what the pub had to offer in terms of real ale, atmosphere, entertainment and accomodation. The primary purpose of this enhancement was to present this information in a more interesting and visibly appealing fashion.

<h3>Objectives for Existing Customers</h3>

- Express the community spirit of the pub in a way that is rarely seen on this kind of site.
- Enhance a sense of familiarity and association with the pub.
- Provide social media links.

<h3>Objectives for Potential Customers</h3>

- Raise awareness of the features and qualities of the pub.
- Provide a visually appealing experience that stands out from the crowd.
- Encourage people to visit, participate in events and book a room.
- Give information about contributing breweries and beers.
- Provide contact and location information.

<h2>Design Features</h2>

<h3>All Pages</h3>

This site uses viewport-based units for dimensions and font sizes, specifically Viewport Width (vh). This was felt to be the best solution for the issue of differing screen sizes, particularly with respect to the alignment of three dimensional elements. Stylesheets are based on screen orientation rather than screen size breakpoints.

Bar pump clips are used to provide a more interesting theme to the site navigation than typical sites. In landscape format they are aligned vertically on a wooden pole to the left, and in portrait horizontally on bar pumps at the top.

Standard text uses a slab serif font called 'Bitter'. As well as it's appropriate name, this font is well suited for the sentences and short paragraphs in which it appears.

The footer includes contact details and relevant links to Google Maps and social media. The dark green and gold colours are a reflection of certain features of the actual pub. 

<h3>Home page</h3>

The 'hero image' animation was inspired by Code Institute's 'Love Running' project.

The introductory lines of text follow the lines of the background image using the CSS shape-outside property. Links to external sites open in fresh tabs.

The centrepiece of the home page is the beer board, a highly recognisable asset of the pub. By making it interactive with tabs that load and reveal text, the qualities and character of the Shoulder of Mutton are highlighted. Different handwritten and quirky fonts reflect the appearance of the real thing! The backboard displays a slideshow of customer images to back up what is stated in the text.

Like the CSS 3D transforms on other pages, positioning of the elements to match the perspective of the photograph was achieved through trial and error. Lessons have been learned should I wish to create similar effects in future projects. The idea for the animated tabs came after reading an article on the [CSS-Tricks website.](https://css-tricks.com/the-checkbox-hack/) By positioning checkboxes off the page and styling the tabs as clickable labels, Javascript is not needed.

A missing feature of the original website is customer reviews. By making them visually interesting they are more likely to be read. Hence the fun invitation to 'Press the alarm!' or 'Click this brick!', depending on orientation, which enlarges the pieces of paper with handwritten and typed out comments.

<h3>Beers page</h3>

When opened the main text is gradually revealed as the level of beer goes down in the pint glass. The text wraps around the glass using 3D transforms, to achieve this it was necessary to divide the text into small sections set at different angles.

At the request of the landlord, links are provided to the brewery websites.

<h3>Rooms page</h3>

Again, a recognisable feature of the pub was chosen to display images of the accomodation. 

<h3>Events page</h3>

This was originally intended to include videos of previous performances, but the files were not available. The photographs on the table temporarily enlarge when clicked, ideally there would have been more so these could be added in the future.

<h2>Technologies Used</h2>

<h3>Languages</h3>
- HTML5
- CSS3

<h3>Frameworks, Libraries and Programs</h3>
- Google Fonts
- Font Awesome
- GitHub
- GitPod
- WeBuilder
- Adobe Photoshop

<h2>Testing</h2>

While building the home page I used Chrome to test as features were added and edited. When I tried it out on Firefox there were a number of issues, so I made adjustments accordingly. From then on it generally paid to develop with Firefox and perfect appearance and functionality here first. Then the result usually worked in other browsers. I also asked a couple of friends with Apple devices to give their impressions. Early on the results were less than perfect but with the help of screenshots and conversations I was able to improve matters.

