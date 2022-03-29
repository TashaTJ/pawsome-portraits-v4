# Testing 

The Pawsome Pawtraits site has been tested in the following ways -

- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator) 
    - [W3C CSS Validator](#w3c-css-validator)
- [Lighthouse](#lighthouse)
- [Responsiveness](#responsiveness)
- [A11y Color Contrast Accessibility Checker](#a11y-color-contrast-accessibility-checker)
- [Browser Compatibility](#browser-compatibility)
- [Testing User Stories](#testing-user-stories)
- [Peer Review](#peer-review)
- [Bugs](#bugs)
    - [Resolved](#resolved)
    - [Unresolved](#unresolved)


## Code Validation 

### W3C HTML Validator

Home Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)

Gallery Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)

About Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)

Learn Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)

Contact Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)

Form Destination Page

![W3C Validator test result](assets/readme-images/W3C/no-errors-small.png)


### W3C CSS Validator 

All pages passed the CSS validator without error. 

![W3C CSS Validator test result](assets/readme-images/W3C-css/W3C-css-congrats.png)

## Lighthouse 

I Used Lighthouse in Chrome Developer Tools to test each of the pages for:

- Performance - How the page performs whilst loading.
- Accessibility - How accessible is the site for all users and how can it be improved.
- Best Practices - How does the site conform to industry best practices.
- SEO - Search engine optimisation. Is the site optimised for search engine result rankings.

After some below 90 scores on initial mobile tests, I compressed the site images and re-tested each page. On these secondary tests, no score came below 94.

- as an example, the results for the Pawsome Pawtraits Home Page for both Mobile & Desktop are below.

![Lighthouse Testing Mobile](assets/readme-images/lighthouse-mobile.png)

![Lighthouse testing Desktop](assets/readme-images/lighthouse-desktop.png)

## Responsiveness 

Responsive design tests were carried out manually using [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/). 

This included:
- Iphone SE, XR, 12pro
- Pixel 5
- Samsung Galaxy S8, S20 Ultra, A51/71
- Ipad Air & Mini
- Surface pro 7 & duo
- Galaxy Fold
- Nest Hub & Hub Max

I also tested on iphone13, Ipad Pro, Macbook and Galaxy Note 8. The only known issues are with the Galaxy fold, where images are not rendering correctly. In future this could be solved via more specific media queires. Otherwise all content and imagery appeared to render as inteneded on all sited devices.


## A11y Color Contrast Accessibility Checker

Colour contrast tests were carried out across the website and all came back without issue. 

![Colour Contrast Checks](assets/readme-images/colour-contrast-example.png)

## Browser Compatibility

The site was tested on Google Chrome, Microsoft Edge, Safari and Mozilla Firefox, with no visible issues for the user. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes and browsers.

## Testing User Stories 

- Understand the purpose of the site on loading

    - The play on words Logo, 'Pawsome Pawtraits' and large Hero image of a hanging dog portrait gives the user an immediate understanding of what the site's main subject is. 

- Navigate through the site smoothly

    - The pages can be accessed in the same way on every page, via a very simply navigational menu, which highlights what page is active by a gold colour change. 

- See lots of examples of artworks

    - There is an extensive second page gallery and then numerous artworks articulating the other pages that the user can browse at leisure. 

- be able to contact Craig easily

    - Craig's contact details appear on a clearly defined 'Contact' page, both via a direct contact form, and then location details below. 
    - Social media links are also apparent on each page as a secondary means of contact. 

- Learn more about Craig's process and perhaps learn some skills myself

    - The learn pages contains a section which breaks down Craig's process for the user, and 3 helpful videos to describe visually how to complete your own portrait.

- Connect with Craig on social media 

    - Social media links appear in the footer on every page without exception. They change colour on hover so the user knows where to go. 

- Learn more about the developer who created the site

    - The developer links also lie in the footer, after Craig's, should the user be curious to visit.

## Peer Review

Prior to launch, the site was submitted for Peer Review by fellow students and alumni at [Code Institute](https://codeinstitute.net/) and also some individuals outside the software development world. Feedback included issues with responsiveness and layout issues, both of which were solved with some minor css adjustments. 

## Bugs

### Resolved

During validation the following bugs occurred.

![W3C Resolved Bug](assets/readme-images/W3C/errors.png)
![W3C Resolved Bug](assets/readme-images/W3C/learn-warning.png)

Both were oversights in the building process and were easily rectified by changing the incriminating file names to spaceless ones and changing the section tag to a div. 

### Unresolved

There is a bug in the learn page which is a sizing and overflow issue, which had I more time I would solve by more experimentation with the current code. 
![Unresolved Bug](assets/readme-images/known-bug.png)

Back to the [README.md](./README.md#testing)