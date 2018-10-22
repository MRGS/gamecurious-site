# Game Curious Draft Site

To test out new Game Curious Montréal website themes

## Site Map

Stuff that actually goes up on a staging or production site:

```   
-- index.md       
-- espacesecuritaire.html       
-- faq.html       
-- css       
-- img       
-- js       
-- vendor    

## Contributing to the games list:

Within each category is a template.md file. 

Duplicate it, and rename it to the game's title, all in lowercase and no spaces. Add in the game's title, the website with no characters preceding the domain name (no http:// or www, for example), the developer's name, the game image's name (usually the same name as the file + png), and a direction (left or right). 

Under the last '---' delete the commented text and add in the game's descriptions, with the higher text for French, and the lower for english. If the game's name is listed in the description, replace it with `{{ page.title }}` and put it in Italics (a single * on each side of the title).

If there are any content warnings, add in `{{ site.cwfr }}` (for french) or `{{ site.cw }}` for english, and put the entire text in bold (double * on each side)

The site will automatically generate the game's description and page after saving.
```

***Stuff that should not go up to a staging or production site:***

```   
-- photoshop (for photoshop files - please do not upload this to an actual site)
-- README.md (this is for GitHub)
-- text (contains word documents with copy in them)
-- .gitignore (this is for git)
```

#### Last Updated October 16 2018
* Graphic design and coding: Zolani
* Design and coding: Gersande
* Additional coding: mstfa
* Translation and copy: Joachim, mstfa and the Game Curious Collective

