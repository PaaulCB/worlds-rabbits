# WORLD'S RABBITS

Worlds rabbit it a site that wants to give knowleadge about the differents rabbits breeds. This site will be targeted towards rabbits owners or any people who wants to have a rabbit pet.
![Website on different screens](assets/images/responsive-site.jpg)

## Features

### Existing Features

- _Navegation Bar_

  - The navegation bar includes links to each section of the website (Info, Fun Facts and Contact Us).
  - Also there is a dropdown menu for the navegation bar on smaller screens.
  - This section will allow the user to easily navigate across all the sections of this website.

    ![Navegation Bar](assets/images/navbar.jpg)

    ![Dropdown menu](assets/images/dropdown-menu.jpg)

- _Info Section_

  - In this section you will find information about each rabbit, such as a description of its breed, its behavior and its appearance.
  - The goal of this section is to provide information about rabbits and the differences between them for people who want to know more about their own rabbit or for people who are thinking about adopting one.

    ![Info Section](assets/images/info-section.jpg)

- _Fun Facts Section_

  - In this section you will find curious facts about rabbits.
  - The goal of this section is to increase the reader's interest in rabbits.

    ![Fun Facts Section](assets/images/funfacts-section.jpg)

- _Contact Us Section_

  - In this section there is a form that needs to be filled out correctly in order to be sent.
  - The goal of this section is for the reader to ask us any questions that have not been resolved when reading the page or to give us some feedback.

    ![Contact Us Section](assets/images/contactus-section.jpg)

- _Footer_

  - The footer includes links to the social media sites for World's Rabbits. The links will open to a new tab.
  - The footer will allow users to keep connected via social media.

    ![Footer](assets/images/footer.jpg)

## Design

### Wireframe

- This is a hand-draw wireframe of the info site on different screen sizes.
  ![Wireframe](assets/images/wireframe.jpg)

### Font and colors

- _Fonts_

  This are the fonts used for this website

  - Amatic SC
  - Kavivanar
  - Sarala

- _Colors_

  This are the color used for this website

  - #36271c
  - #d5bdaf
  - #D7CAC1
  - #f5ebe0

## Testing

### Manual testing

- _Lighthouse report_
  Lighthouse report results that we run in incognito mode
  ![Lighthouse report](assets/images/lighthouse-report.jpg)

### Validator testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fpaaulcb.github.io%2Fworlds-rabbits%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fpaaulcb.github.io%2Fworlds-rabbits%2F&usermedium=all&vextwarning=&warning=1)

### Fixed Bugs

- Pressing any option on the navbar took you where it should but having a sticky header, it covered part of the content. I fixed it by giving this property to the body with the height of the header:
  > scroll-padding-top: 51px;
- On larger screens the content was displayed in a single row instead of showing 2 elements per row. I fixed it using CSS grid instead of flexbox:

  > display: grid;

  > grid-template-columns: auto auto;

### Unfixed Bugs

- Pressing any menu option on small screens takes you where it should, but does not close the menu afterwards. This bug is still not fixed because I have not found a way to fix it using only HTML and CSS.
