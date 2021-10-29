### Outline for CSS Guidelines video

## Title
5.49 Tips to Write Better CSS TODAY
## Intro / Hook

Today we are going to cover 5.49 Ways that you can write better CSS starting today.

I got these from an amazing article written by Harry Roberts at cssguideline.es. 

I'm not going to cover everything in the article Just the things you can start using today so when you're done watching this video I highly reccomend you go check it out a link will be in the discription.

## Content
 #### 1. Use Multiple Files.
 - whether you are using a build tool like sass or vanilla css you should break up your css into multiple files.
 - with vanilla css just import them at the top of your HTML, just remember that css uses source order to determine which styles to apply so the files being imported  below the others could overwrite them if targeting the same element with the same specificty.

 (b roll of using multiple files into an html doc)

 #### 2. Titleing - using comments to mark parts of your code. Applies to CSS and HTML. 

 - this one is as simple as it is powerful, put labels on large chunks of code.

 - It just makes there be 1 less thing you have to search for and you can free up your focus to solve more important problems than getting lost in your own code.

 - using a '#' in front of the section title make it easy to search for that section and immediatly find it.
 
 (then show b-roll of that example)

 #### 3. Use a naming convention, CSS naming conventions is a really deep topic that desrves it own video.
 (show simple BEM example and explain it doesn't have to follow the paper trail of your html) but if you just want a place to start learning BEM is good because it's the one you're most likey to run into in the wild.

 - I'm sure you've heard about BEM before. the simple explination is its a wy to flatten specificty and use to create namespaces for our css.


 #### 4 alignment and indenting
  - align values of related rules, it's a simple thing but it makes your code look like it was written with so much more intention.

 #### 4.99 . Use whitespace
  - One (1) empty line between closely related rulesets.
  - Two (2) empty lines between loosely related rulesets.
  - Five (5) empty lines between entirely new sections.

## Call To Action