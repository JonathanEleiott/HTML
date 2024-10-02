# HTML and more Git Workflow

## HTML

- Structure of your website
- elements -> what the browser reads and displays to the user
  - tags
    - name
    - opening
    - optional: closing
  - content

- general structure of a webpage
  - html -> contain all other elements
  - head -> information that the user will NOT see on the page (metadata)
  - body -> information that will be displayed to the user on the page
  - title - displayed in the browser's tab

- formatting "rules"
  - HTML files should be named in lowercase and separated by hyphens
  - convert tabs to 2 spaces
  - avoid leaving trailing spaces
  - elements inside of other elements should be intendted one time (2 spaces)

- semantic elements -> named based on what's inside of them
  - header -> top of the page and contains logos, introductory content, navigation
  - main - between the header and the footer -> main content (articles, information, products, etc.)
  - footer - at the bottom containing contact info, address, special links, back to top link
  - h1-h6 -> header 1 (title) (largest) - header 6 (smallest)
  - nav -> navigation - nav bars
  - a -> hyperlink (anchor tag)
  - article/section - grouping of content
  - img -> shows an image
  - ol/ul - ordered list (numbered) /unordered lists (bullet points)
    - li - list item
  - p - paragraph

- non-semantic elements
  - div -> divider
  - span

- advantages of semantic HTML
  - Search Engine Optimization (SEO)
  - Screen Readers
  - Working with humans

- attributes - give additional info for the element

- comments
  - do NOT display in the browser

- troubleshooting and debugging
  - ALWAYS write and test your code as you go!!!
  - are you missing a closing tag
  - are there spelling errors
  - comment out certain parts of the code to find the broken code

Chrome Dev Tools - function F12 or right click + inspect

## More Git Workflow

- Merge Conflicts
  - happens when two people change the same file without pushing/pulling the changes first

- Branches
  - git checkout -> change branches
    - -b <feature-name> -> create a new branch
  - allows working on a new feature without affecting the main branch (production)
  - very, very, very important when working in groups

- Pull Requests
  - allows for a second set of eyes to catch any bugs
  - 1st person -> GitHub -> Make a Pull Request (at the top)
  - 2nd person -> GitHub -> Review the commits on the Pull Request -> Approve and merge OR tell person 1 to make some changes first
