# Beamer theme - University of Trento
 
This project aims to code a LaTeX beamer theme for master's & bachelor's degrees of the University of Trento (Italy), but also to provide a quasi-official theme for professors, students, et cetera working or studying at UniTn. As of now, this is a _non-official_ project. The theme will follow current guidelines for style and impagination.

Latest version: `v0.2-beta2`, may 2021

![immagine](https://user-images.githubusercontent.com/64229723/115863144-54ed6c80-a435-11eb-870e-804b5819b2a7.png)

### colours & themes

The theme is currently available only in **math** and **physisc** versions, we'll soon add some other departments. We will also add different colours, and various other settings.

## HOW TO USE:
The second beta release is available! However, the project is still marked as incomplete... therefore you might run into some issues.

In order to use it you will have to 
1. insert in your main folder the .sty files you will find here,
2. add into an `images` folder the images you'll also find here,
3. call as usual the `\usetheme{beunitn}` command in your beamer document; this will require setting the right options, i.e. `\usetheme[math]{beunitn}` or `\usetheme[physics]{beunitn}`.

You should be able to fully customize the theme according to your personal preferences. See `NOTES` for a dummy test of its functionality.

## HOW TO CONTRIBUTE: 
It is possible to contribute to the development by testing the package and informing us of possible errors or limitations. Check `HOW TO USE` for more info. 

## NOTES:
This theme is currently incomplete, but it's already possible to use it; be warned you'll may encounter some unresolved issues. It is also possible to just test it (see: `tests` folder). 

# USEFUL LINKS: 
- It may be helpful to consider [this discussion](https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch) on stackexchange. 
- A [second take](https://www.r-bloggers.com/2011/11/create-your-own-beamer-template/) on Beamer customization.
- If you are italian, [this PDF](https://www.guitex.org/home/images/doc/GuideGuIT/intropersbeamer.pdf) will help you a lot.
- For a short tutorial on frame titles, [consider this website](https://bloerg.net/posts/customizing-the-frametitle-of-beamer-presentation/).
- To edit the README file: [useful info](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).
- Beamer appearance: [cheat sheet](http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf)
- Beamer geometry sizes: [picture](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftex.stackexchange.com%2Fquestions%2F34367%2Fbeamer-frame-without-decorations-with-custom-margin&psig=AOvVaw1btF3iM-dko9MQgSazc4Ph&ust=1619707212640000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCICm-dqVofACFQAAAAAdAAAAABAO)
- Write a beamer theme, an example: [stackexchange](https://tex.stackexchange.com/questions/261185/issues-with-custom-beamer-theme)
- Footline: [useful info](https://tex.stackexchange.com/questions/167648/beamer-navigation-symbols-inside-footline)
