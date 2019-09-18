# Among Unfinished Projects
There are many more projects and project ideas than there is manpower and know-how to finish them all. I am especially calling out to budding programmers, junior developers, who have a passion for computer vision or web development and seek reallife projects to learn and hone new skills: join us and make a contribution, small or great, to open source software projects that will be used for cutting edge research in the humanities.

## Who we are looking for
We are looking for someone who is great at working out problems independently. You should be able to allocate time to finish a project once you start. Most importantly, you can prove or reasonably argue that you have been learning at least one of the following technologies for at least six months:
  * Python 3.6+, with a strength in at least one of the following:
    * OpenCV
    * Matplotlib
    * NumPy
    * NLTK
  * Django or Flask
  * JavaScript, with a strength in at least one of the following:
    * Vanilla JS
    * Frontend library, preferably React (if not, perhaps you know Vue or Svelte?)
    * Backend library, preferably Node and Express (if not, perhaps you know Meteor?)
  * Web design skills relating to:
    * fonts
    * vector graphics
    * UX
    * UI

## What we offer
You will be working closely with humanities scholars from around the world. The actual goal, road map, and preferred technical solution will be given to you. During the project coaching will be available. Publications based on research made possible by your technology will cite you. We will be happy to help out in other ways, if necessary.

# Projects in need of help
**1. Basic OCR Pipeline**
This project will lead to a user-friendly piece of software that transforms a digitized printed publication into a digital text file with reasonable accuracy (>95%). Current target scripts include Latin and Arabic. A Python script should do the following:
* *reduce PDF to images* : Users will typically take a PDF from e.g. Archive.org
* *provide UI* : Users need to highlight stuff on pages that is 'garbage', e.g. footnotes, punctuation, etc.
* *clean up images* : script should white-out all the garbage
* *parse to Tesseract* : script should detect lines and send images of seperate lines to Tesseract (which handles the OCR), then receive text back
* *store as TEI* : text should be stored on disk with limited mark up, including page number, and line number.
* *assess quality* : automated check for accuracy with several degrees of possibly weak OCR. 
* *correcting text* : UI comparing original image of page with OCR'ed text with visual clues of degree of certainty, with possibility for user to manually correct.

**2. Interconnected Who's Who of 15th c. Cairo**
We have a text file with on every line an entry, about 9000+ of them. Each entry is a short biography of someone in or connected to fifteenth century Cairo. We need to achieve two things:
* Entries should be connected if they share information, such as same city, year, teacher, student, book title, legal affilitation. 
* An interface should disclose the entries and their relations in a user-friendly manner, possibily with tools to manually add relationships.
