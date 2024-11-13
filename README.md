# Prevent: Safeguarding in a Dangerous World

### A project utilising HTML, CSS, Bootstrap and relevant AI tools. https://philgck.github.io/Prevent-project-1/

The intent of the website was to provide a single point for anyone looking for information about prevent, what the prevent programme does, how to spot the signs of radicalisation and as part of the wider information about prevent, some criticisms. This was split into 4 key pages, one providing an overview and being the home page, also containing a glossary of terms. “What it is” is dedicated to more specific knowledge about prevent and the core aspects of the prevent strategy, alongside a link to the specific guidance for those who needed more in depth information. “How you can help” is dedicated to the warning signs that someone can look out for and some strategies. “What it should not be” is dedicated to some criticisms of the prevent project, to remain more balanced broadly and as part of achieving the goal of providing someone with an overview of prevent. 
 
In the top left there is a “Leave this website immediately” button that is always visible, an idea I saw on a council website that I looked at as part of research ahead of the project. Many websites that cover safeguarding issues have similar, as it is essential that someone be able to quickly leave a page if the person they are concerned about is potentially able to see what they are looking at. The nav bar as a result is always pinned to make sure that you can easily see where to go, and how to leave quickly. The nav bar was styled to make sure that on smaller screens the quick escape button is still visible. 

Each page uses a combination of flex or bootstrap in order to maintain responsive design. The website was first designed to look good, clear and readable on mobile phone due to the mobile first approach, and at different break points the content on each page expands to better utilise the space. I tried to make sure the same amount of content was on each page, and that each page had a similar design ethos, with the exception of the page that covers warning signs to consider: There are simply too many categories or signs. The How You Can Help page was therefore styled using bootstrap cards containing lists, broken into two equal sized columns per row. 

Microsoft copilot was used to generate the hero image and one other image, although it did not make it into the final project. Despite specific prompts, I found image generation using AI tools to take far more time than it saved, and considering the informative nature of the site, I made the decision that having images associated with each card or block of text on the site would be a nice feature, but not an essential one. Below is an example of my frustrations with AI tools:

![image](https://github.com/user-attachments/assets/8d840630-6743-43f3-9df0-81fcb354ebfa)

In the future I would try and avoid using AI generated images as anything but placeholders. With further time and scope I would have relied on one of the artists I know, however with the time pressures of this project I didn't feel comfortable getting them to rush it through, and realised that the site might feel cluttered with excess imagery. 

With regards to code, copilot was only used to streamline the completion of tasks that I had already done at least once: I found some of the suggested prompts to be unhelpful. Further, I kept receiving error messages about the ethical use of AI when asking it for assistance with tasks. From a brief search, it appears that sometimes copilot will refuse to work on tasks that are associated with certain subjects, and I believe the content of the site itself and the resultant references to terrorism or extremism might have been flagging the output. Chat GPT was used to generate the list of warning signs for extremism, and the content itself was then double checked in order to make sure that it was accurate and made grammatical sense. 

The text and colour scheme were created after consulting a guide on dyslexia friendly fonts and colour schemes. Had I had more time, I would have considered styling the site itself differently and adding accessibility features that restyled the site. However considering the time constraints and the fact that the site was largely textual in nature, I simply thought it expedient to set up the entire site to be dyslexia friendly in the first instance.

# Project Planning

Initial Wireframes:

![image](https://github.com/user-attachments/assets/b4b3f156-4c76-41f9-b289-17270423f6fe)

![image](https://github.com/user-attachments/assets/09c218c3-095a-4f81-9c5e-c21a5ed27423)

The intial wireframes assumed the cards would be smaller and arranged differently, with images associated with each card. You can see the original outline of the nav bar, and its changes. 

![image](https://github.com/user-attachments/assets/4037f2af-4707-4dc5-874d-f26f0501e296)

The finalised wire frames were simple: 

![image](https://github.com/user-attachments/assets/3ea79fd8-3f25-452c-ac59-40022e3ef79a)

![image](https://github.com/user-attachments/assets/1945c002-4a4d-4355-a25c-182f9bf0cd94)

With the rough guide stuck to on each page, and some variation done to provide cohesive design between each page. 

I used copilot to generate a series of user-stories, which I then tweaked in order to create a list of 5 users with different needs in order to keep the project on track. 

Had I had more time, some other features I was wanting to add included a carousel of images to watch out for, and some links to moderating tools for online communities. However, I found it surprisingly challenging to find a list of relevant British images that I felt comfortable using: The two clearest sources were from counter-terror police and an article from the Guardian referring to a leak and I decided against using images from a leaked document. I briefly considered using a few of the images published by the Anti Defamation League for this instead, however considering they are an american organisation many of the images were less relevant. For this task I did not think it possible, nor felt comfortable, trying to get an AI image generator to create what would inevitably be fascist symbols. 

# Validation and Testing

During testing I found some issues with the iframe on the What It Should Not Be page, which were corrected by adding a minimum height. However, despite width 100% being flagged by W3C, it seemingly works. Frameborder is now flagged as obsolete, which was copied across from the youtube embed link.

W3C CSS Validation found an error in the secondary font, which was not working due to a missing ;, and corrected. After this no errors were found.

W3C HTML Validation found that I had accidentally placed the nav bar outside the body tag, once this was corrected no more errors were found. 

# Lighthouse Report

![image](https://github.com/user-attachments/assets/280e3fc8-ee66-47cd-9c82-2bf08b42e5a7)

On mobile phone, the site paints too slowly. Javascript has slowed down the first paint of the website. Even with a compressed hero image, it still slows down loading.

![image](https://github.com/user-attachments/assets/7d8fd43c-4eb7-43ce-8163-d5987cd51d9c)

However, the lighthouse report for desktop is much more positive.

Lighthouse testing was missed until too close to make changes.

# Research and attribution:
https://fontjoy.com/ - Was used to select fonts.
https://business.scope.org.uk/how-to-write-better-website-content-for-people-with-dyslexia/?gad_source=1&gclid=CjwKCAiAudG5BhAREiwAWMlSjBDhEAM1GdpOaoBXOYHiZGdwXwxH_DFxMmcWaH4n-bCWUK3gwQRSsBoC69UQAvD_BwE - Used to make sure the website was easily viewed for people with dyslexia. 
https://www.gov.uk/government/publications/prevent-duty-guidance - Was used for research for the project. 
https://www.bdadyslexia.org.uk/advice/employers/creating-a-dyslexia-friendly-workplace/dyslexia-friendly-style-guide - Also used to make sure the website was easily viewed for people with dyslexia. 
https://www.counterterrorism.police.uk/what-we-do/prevent/ - Was used for research for the project. 
https://blogs.lse.ac.uk/lsereviewofbooks/2014/07/08/book-review-the-muslims-are-coming-islamophobia-extremism-and-the-domestic-war-on-terror-by-arun-kundnani/ - The Muslims are Coming, Arun Kundinani. Reading this in the past is what has given me a wider understanding of the prevent programme and contextualised some of the criticisms, which is why I felt it important to include them from an ethical perspective.

Dandarr: Friend with dyslexia used as an external tester. Flagged issue with the list items.

![image](https://github.com/user-attachments/assets/d6eb06ed-fdc3-4f91-aca3-4be6e565f18d)

