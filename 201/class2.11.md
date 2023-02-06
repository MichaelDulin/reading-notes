# Class 2.11 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 11**
- [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [From Objects to iframe - Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

**Video / Audio Content**
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
  - Early WWW applications were limited in user interface, required extensions and were not accessible
2. Describe the use of the src and controls attributes in the <video> element.
  - The src behaves the same way as img src (url to video) and controls allow the user to customize their viewing experience
3. Why is it important to have fallback content inside the <video> element?
  - Allows for a contingency of different supports for browsers or a link to a different site with the video
4. Write a very short story where <audio> and <video> are characters.
  - The video tag is like the older brother with larger size and can do more, while the audio tag is the little brother who doesnt take up much size
  
**Complete Guide to Grid**
1. How does Grid layout differ from Flex?
  - Grid is a better wat of designing our UI and is two dimensional while flex is one directional flow, but they can be used together
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
  - Grid Container: direct parent of all grid items (display: grid)
  - Grid Item: children of the grid container
  - Grid Line: dividing lines which make up the structure of the grid (horziontal or vertical)
  
**Responsive Images**
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  - Spacing could affect entire flow of site or presentation, also an issue for differing display quality
2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
  - srcset defines a set of images the browser will choose between for different sizes. 
  - sizes defines a set of media conditions to choose which image will be best to use
3. How is srcset more helpful for responsive images than CSS or JavaScript?
  - srcset will load first to determine screen size and resolution before uploading photos while javascript and css will only display as 'img' and will load the default image regardless of which screen is being used

## Things I want to know more about
