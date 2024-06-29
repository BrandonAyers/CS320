# CS320

How can I ensure that my code, program, or software is functional and secure?
The best way to ensure that code is functional and secure is to do testing. We've learned this throughout the last few weeks. When testing you shouldn’t just be focusing on meeting requirements but ensuring that the code is secure. I made a lot of good test case in the first section of Contacts but forgot that I wasn’t checking to see if the user entered a bunch of blank spaces. I checked for Null values but I was unsure if this would catch someone entering a spaces. I was able to mitigate this by creating a new test case to check for this. This ensures that the code is secure but also meets the requirements set by the customer.


How do I interpret user needs and incorporate them into a program?
The user needs were very easy to understand and I couldn’t be happier with the outcome. There are a few issues I ran into but the best course of action is to check for all possibilities. The user needs said to check for values under a certain amount of characters that aren’t Null. The first part of being under a certain amount of characters is easy to understand and requires checking for values that are under and over that amount. The second part of Null can be interpreted in a few ways. At first I thought just checking for Null was sufficient but going back I realized that I should check for someone entering 8 spaces. My knowledge of Java is that it treats spaces as having a length so this is something I’m glad I changed to check for. 

How do I approach designing software?
My approach for designing software is different with each project but this one was based on a Incremental design. This allowed for me to create code and keep adding to it in increments. This was shown with each module by adding more classes. I start with writing a document of the requirements I need with the different values. I then think about the possible test case before I even start coding. After these are done I create my code and review it before doing testing.
