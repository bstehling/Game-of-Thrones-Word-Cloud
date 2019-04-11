# Game-of-Thrones-Word-Cloud

Please watch the following video for an overview of the web application: 
https://youtu.be/aLZEWoGJAWg

Web Application Link:
https://bstehling.github.io/

The purpose of this web application was to display the analysis of the names found in each of the books from A Song of Ice and Fire by George RR Martin. It shows the co-occurence of each of the major characters 
as well as a word cloud of the most commonly mentioned characters. Each are based on the book selected by the user and the co-occurence is based on the number of times characters appear in the same chapter together. 


## Some interesting findings: 

1. Co-Occurence Matrix: Story lines are formed individually then slowly blended

From the first book we see there are groups formed that show a strong distinction and a seperation from other groups. As we begin to see in the second and third book, those story lines of each group come more and more together as the stories begin connecting. Lastly, with the final two books the groups are much harder to find groups in as now all the stories are one large storyline. 

<img width="200" alt="Screen Shot 2019-04-11 at 1 36 01 PM" src="https://user-images.githubusercontent.com/45048090/55984756-c9e11580-5c63-11e9-8b81-88e6d8de3379.png"> <img width="200" alt="Screen Shot 2019-04-11 at 1 36 20 PM" src="https://user-images.githubusercontent.com/45048090/55985041-7e7b3700-5c64-11e9-9933-1cb5bdfd6c2c.png"> <img width="200" alt="Screen Shot 2019-04-11 at 1 36 35 PM" src="https://user-images.githubusercontent.com/45048090/55985064-8f2bad00-5c64-11e9-8920-2eb6d709ab68.png"> <img width="200" alt="Screen Shot 2019-04-11 at 1 36 57 PM" src="https://user-images.githubusercontent.com/45048090/55985091-9fdc2300-5c64-11e9-902c-186ede1749bf.png"> <img width="200" alt="Screen Shot 2019-04-11 at 1 37 13 PM" src="https://user-images.githubusercontent.com/45048090/55985096-a2d71380-5c64-11e9-9ac0-c117c616a171.png">


2. Word Cloud: Character appearances and disappearances throughout the books 

For the word cloud, we chose to display the top 20 most frequent characters mentioned in the book series. The reason for this is that there are hundreds of chracters and some only get mentioned a few times versus a few hundred times. Some names begin to grow in frequency throughout the books just as some die down, changing the importance of the characters as the novels evolve. However, in the last two novels we see a major switch from the most common characters. This peaked curiosity amongst us and, after looking into the reason, we found the author split the conclusion of all the characters and their story lines in two. He wrote an explanation at the end of book 4 telling how he had so much to write about each characters conclusions that it needed to be broken in two books. The reason we see completely different highest frequency names in each book is because he "felt that the readers would be better served by a book that told all the story for half the characters, rather than half the story for all the characters." **(SPOILER ALERT)** We can also point out that some of the major characters represented in the word clouds completely disapear in the further books. This is caused by the plot. Some characters, like Eddard(Ned) Stark for example, appear as the most frequent chracater in the first book and then are not shown in the second book. It happens that Ned Stark was beheaded in the plot of the first book, so he is no longer mentioned enough in the following books to be displayed on the word cloud.

<img width="350" alt="Screen Shot 2019-04-11 at 2 30 04 PM" src="https://user-images.githubusercontent.com/45048090/55987413-1e39c480-5c67-11e9-9d8a-addc16f3723a.png"> <img width="350" alt="Screen Shot 2019-04-11 at 2 29 56 PM" src="https://user-images.githubusercontent.com/45048090/55987418-2134b500-5c67-11e9-9f22-119c5d10f36d.png">


## Contributions

This project was created by three developers including Brandon Stehling, Elizabeth Doyle, and Matthew Hendrick. We split the work up into sections so that we could handle the project in the short time frame that we were given. 

Matthew Hendrick worked on the initial data collection of the Song of Ice and Fire texts. We originally used owned copies of the epub files and converted them to text files. Matthew created the specific file formats with the character frequencies by using Java.

Brandon Stehling implemented the word cloud in D3 using Jason Davies' implementation which you can find here: https://github.com/jasondavies/d3-cloud
By combining the text files from the books with the D3 word cloud implementation, Brandon was able to create custom word clouds for each of the 5 books in the series to display.

Elizabeth Doyle implemented the co-occurence matrix relating the characters in the books to one another based on whether or not they have appeared in the same chapter of each book. The data used for this part of the project was acquired by using C++ to extract the matrix values for each book. The implementation was completed with the help of other online resources found on: 
http://bl.ocks.org/Lichtphyz/88ba061011589c805eb016d0f9d61a79/5f9a16cb8f32c8d0af3713fa45e252dff80ea74a

Altogether, we were able to display the co-occurence matrix and the word clouds by each book selected through a drop down.
