# homework-1-css Code Refactor:

- In order to do this assignment I began with the overall order of the code, then i continued to analize what could be simplified. and finally i had to figure out a way for the nav and the sections to stay in place without overflowing.

1. First I went to the code and replaced the divs with both section and aside elements. this was done to differentiate the two sections.  The section element was set for the sections of:
* search-engine-optimization
* online-reputation-management
* social-media-marketing

2. Then I expanded on those sections by ading alt tags for each image 

3. I continued to discard all indidual style tags because it was redundent to write it over and over again and replaced it with job classes. and finally I established the main tag since the other section was so small in comparison.
 
4. I then focused on the next set of div tags and added an aside tag. this was done because with "aside" it be easier to read which section is floating right since the other 3 divs were already assigned a float-left.

4. I restructured the individual tags following (benefit-lead, benifit-brand,banifit-cost) to a singular benifit class because again its redundant and the foundational structure of the "aside" was established simpler with a "benifits" tag and it was organized for html.

5. finally, I focused on the first div section and set the links to unlisted which was sorrounded by a nav tag to keep the elements enclosed within. The header was set with a "overflow:auto" style element to keep both the "horiseon" title and the nav section from escaping when the page shrinks.

6. i figured that I could do the same for every section element so in the assigned "job" class and within the element I placed a "overflow-auto" correction.

7. Lastly, I replaced the footer class with a footer element.
 
8. the git depository was then created and pushed my work there.