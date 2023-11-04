
When going through the site I noticed immediately that it relied heavily on CSS and was likely written in either HTML or Markdown formatting language. Having always been very personally vested in design across various mediums as a personal hobby, and frequently editing intranet sites, desigining mobile applications and publishing newsletters within a government professional level - I can comfortably recognise how a few design elements were done. 

My first thought was this would not be able to be accurately recreated using Microsoft word, so in the aim to most accurately recreate the look and feel of the articles on the Washington University website, I elected to begin drafting the article layout in Obsidian - which is a markdown editor that allows various web based languages like markdown, html, css and javascript to be used and displayed - with the output being able to be published to PDF directly. 

--- 

My takeaways from the site were immediately that it was very focused on modern accessible design elements. The use of purple and beige is quite popular in modern designs. The font was also immediately recognisable as Open Sans, which is a popular choice in modern websites as the font is accessible and being sans serif gives a modern feel, however its also not drastically different from more traditional fonts like arial or calibre, the reader gets a 'fresh' impression and the font does not have to risk being too different. 

Many articles use padding and reflexive text justification, so the text and window dynamically change based on the device it's displayed on - however with the padding the feel remains consistent. 

---

Tonally the text of the article itself is written in a way which is generally positive in nature, regularly expressing appreciation or support of the topics featured, and is overall optimistic with a forward looking approach. 

Typically it seemed the flow of the articles use a narrative style to establish the context of the story, before addressing the relationship of story in a present day as well as looking forward to keep an overall positive tone, and addressing future implications. 

Its a comforting style that reaffirms the validity of what the author is writing about through either direct quotation or drawing on various departments within the university or other industry experts to solidify the validity of the text with the reader. When necessary this is further solidified through appropriate use of technical jargon, it's used sparingly enough which refrains from alienating readers who may not be versed in the field, however the instances in which it is used builds toward the credibility of the pieece, serving almost as a reminder that while the tone is accessible the quality of the text is not without factual basis. 

Anecdotal evidence is also used quite freqntly, which is used generally as a seeming segue when going into future discussion or implications of the story on the future. It gives a humanisitic style to the piece, with accessible language and once again evoking a generally more uplifting tone.

--- 

# Editing Process

Getting a 36 page document into 450 words requires eviceration of all the fat, and leaving nothing but engaging content that would entice the user to access additional resources to learn more. 

A fantastic trick in web development is that as most sites are written in a combination of HTML, Javascript and CSS - you can often recreate entire websites simply by inspecting the websites source code and replicating the elements you want. 

My first honest thought was to simply replace all the text within the site itself with my restructured content from the article and export the site to a pdf document - which while I did confirm works I felt it was not in the spirit of the assignment as the design and layout choices were already predetermined - although I do believe one of the examplars used this exact method, so maybe i'm just creating additional work - productive procrastination!

Instead I decided to recreate it in Markdown as this would be more honest. I started with acquiring a higher resolution banner image for the site. As I could not match the category sections beneath the UW news title, I did have to just modify that text from the website itself along with the date, before exporting to the editor. 

---
# Image 

In industry standard fashion, the article features a prominent hero picture, so that was next on the agenda. The article I chose is "Discursive Communication Strategies for Introducing Innovative Products: The Content, Cohesion, and Coherence of Product Launch Presentations" by Huiyu Zhang , Yiqun Song , Yuanhong Wei and Jingjiang Liu. 

- The image therefore I knew had to be relevant to the topic
- It had to be consistent with the branding and simplicty of the UW news website
- I wanted to remain in stylistic theme and use negative space as is commonly used to emphasize images on the UW news site. 
- The placement of the image would need to be unobtrusive and allow the title and introduction of the article itself to remain easily readable and keep a good natural flow as the reader engages with the article. 
- In studying articles on the website, I noticed that many of the design principles are in line with gestalt psychology, particularly 
	- proximity and the relation of the article title & iintroduction to the image establishes a direct relationship between the image and the content. 
	- Closure is used often as the images are commonly quite simple allowing our brains to complete the picture, it shows simply the subject allowing our brain to extrapolate the image details 
	- Similiarty is used and the image palletes often compliment that of the website itself, establishing cohesiveness. 

For the image, I elected to use DALL.E 3. I chose to go this route as it would reduce the time required to obtain an image, and I would have direct control to get an image I believe would best fit this article. 

Innovation, communication and strategy are words which ellicit a modern image in my mind. Communication and innovation i associate with a strong image of Steve Jobs' announcement of the first iPhone. An inspiring presentation which really made me feel like I was in a way living in a science fiction world for a moment. 

I decided I wanted something with a podium, centre stage of the image naturally drawing attention without having to compete for it - the concept is simply interesting enough that the audience is naturally drawn to it. 

Communication I understand to be flowing and something which is almost free spirited. In keeping inline with the gestalt principle of proximity, I designed a mock up image of a podium with speech bubbles at differing but close proximity to a podium microphone. 

In keeping with the palette of the website, I wanted a gradient from a beige adjacent colour like in the banner of UW news, to the indigo used in the title, allowing for a natural transition from the image to the title colour. 

After some prompt modification, I found something acceptable with asking for an image to be generated with a soft gradient background moving from beige to a darker colour near the bottom. Central to the image is a microphone on a podium, conveying a feeling of being at a product launch. Surrounding this a variety of curved lines, arrows and speech bubbles with miscelannous content in close but varying proximity to the podium. The colour palette should be consistent throughout the image and not feature any sharp transitions. The image should appear modern and sleek, and offer opportuinty for the viewer to mentally complete parts of the image in some way. 

This resulted in the image below and I moved on. 

![[DALL·E 2023-11-03 20.23.34 - Photo of a soft gradient background from light color at the top to a darker shade at the bottom. In the center, a modern metallic podium with a sleek .png]]


--- 

# Colours 

Next, I modified my text editing client with some CSS code to feature the same background colour as the website, and used a hex colour picker to get match the same indigo from the headings to ones I would create in the editor. 

I used powertoys for this, and got the hex key 463180. 

The blue colour for the hyperlinks was slightly more challenging as they change colour when hovered over. For this I inspected the style sheet of the website and found the colour used; 0074bb & when hovered over 827651. 


---
# Editing The webpage

Websites are quite interesting in the sense if the site is built using HTML, Javascript, CSS or other formatting languages, you can replicate elements from different sites by modifying the code of the site you wish to place it in. 

This of course is not live, but it allows complete control of the site content locally.

First step was changing the title, author name, image caption and attributing the source of the image. 

When viewing one of the articles I saw they used block quotes to good effect, and wanted to replicate that in my article. I located the position I felt the quote should best be displayed, beneath the image, and using HTML created a new blockquote division. As the site already has a style sheet setup, this worked quite easily. I modified the block quote text colour and font weighting to immediately draw attention to it, similar to steve jobs' presentation style I wanted to try and emulate the setting up the narrative style of presentation as an ode to the article. 

I chose the colour of the washington news site beige banner, as I wanted to associate the quote with authority and credibility, so piggybacking off the colours used by the banner subconsciously the user is associating the quote as being important / credible. 

I didn't like the spacing of the blockquote and the author credit in relation to the rest of the article, so the next step was modifying the padding and margins of the block quote to clean it up a bit. Using nonbreaking spacer codes I was able to shift the author to the right hand side of the quote, so as to not detract from the quote itself. 

I wanted to use hyperlinks to add to the article in ways that would improve accessibillity and convenience for the reader without unnecessarily literring them throughout. I provided a link to the journal article attached to the author names

Headings were used to rbeak up content where relevant, and allow users to skim through the article and quickly pull out or get directly to information they want to see. Headings are unobtrusive and match the colour purple used throughout the website maintaining consistency

--- 
# Footer

I tried to recreate this but quickly decided to screenshot the element. 

--- 
# Discursive Communication Strategies for Introducing Innovative Products: The Content, Cohesion, and Coherence of Product Launch Presentations