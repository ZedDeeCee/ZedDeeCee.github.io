---
layout: post
title: "How to use Amazon page count as a criteria for literary competitions"
date: 2021-08-07 01:00
author: Zed Dee
comments: true
summary: "Don't."
image: /content/images/AmazonPages.JPG
---

Don't. Never ever use Amazon page count as a criteria, at least as a proxy for word count. The recent Self Published Science Fiction Competition asked for 50,000+ words as their entry criteria but changed it to 200+ Amazon pages on the assumption that 1 Amazon page == 250 words. I've also been told that the Self Published Fantasy Blog off also uses a similar criteria (not sure if it's true or not).

First of all, 1 Amazon page != 250 words. Here are some numbers from books in my library that are DRM free.

| Title | Author | Microsoft Word Word Count | Amazon Kindle Pages | Words/Kindle Page |
| :------------- | :----------: | :----------: | :----------: | -----------: |
| Remembrance of Earth's Past | Cixin Liu | 537,348 | 1544 | 348.02 |
| Ninefox Gambit | Yoon Ha Lee | 99,349 | 265 | 374.90 |
| Prey of the Chance | Snigdha Ramkumar | 85,639 | 215 | 398.32 |

| Title | Author | Microsoft Word Word Count | Amazon Real Pages | Words/Real Page |
| :------------- | :----------: | :----------: | :----------: | -----------: |
| Wool | Hugh Howey | 158,654 | 594 | 267.09 |
| Oathbringer | Brandon Sanderson | 458,430 | 1220 | 375.76 |

As you can see, none of them are close to 250 words per page.

But wait, why are there two tables? What is a "real page" and a "kindle page"? As far as I can tell, there are three types of page counts. Some page counts have a down arrow beside them, which if you click will tell you if they are based on a print edition or if they are based on Kindle page turns. There is a last type with no arrow and I have no idea what that means.

So how do you actually enforce a word count criteria?

1: Install Calibre from [https://calibre-ebook.com/download](https://calibre-ebook.com/download){:target="_blank"}

2: Open Calibre and go to Plugins under Preferences

![Step2](/content/images/CalibreStep02.jpg)

3: Install the Count Pages Plugin by clicking Get new plugins, entering "Count Pages" in the search field and clicking install 

![Step3](/content/images/CalibreStep03.jpg)

4: There will be a popup warning about installing plugins being a security risk. Click yes unless you want to do the word count book by book.

![Step4](/content/images/CalibreStep04.jpg)

5: Restart Calibre after the plugin has finished installing

![Step5](/content/images/CalibreStep05.jpg)

6: Go to Add your own columns under Preferences

![Step6](/content/images/CalibreStep06.jpg)

7: Click Add custom column and fill in Lookup name with "wordcount", Column heading with "Word Count", Column type with Integers and Format for numbers with "{0:,d}". Then click OK.

![Step7](/content/images/CalibreStep07.jpg)

8: Click Apply and Restart Calibre

![Step8](/content/images/CalibreStep08.jpg)

9: After Calibre has restarted, drag all the entries of your competition into Calibre

![Step9](/content/images/CalibreStep09.jpg)

10: Select all the books in your library, click the little down arrow next to convert and do a Bulk convert

![Step10](/content/images/CalibreStep10.jpg)

11: Make sure the output format is EPUB and click OK

![Step11](/content/images/CalibreStep11.jpg)

12: If you got some epubs along with some mobis you will get a convert existing popup. Click No.

![Step12](/content/images/CalibreStep12.jpg)

13: When the job is complete, as shown by a Jobs: 0 in the lower right corner, click on Count Pages.

![Step13](/content/images/CalibreStep13.jpg)

14: When the Count Pages job is complete, there will be a popup. Click Yes.

![Step14](/content/images/CalibreStep14.jpg)

15: Now you have word counts for all your entries.

![Step15](/content/images/CalibreStep15.jpg)

Quick and easy-peasy. Notice that once you do step 1-8, you never need do them again, and to get word counts for any number of books, you will only have to do a total of 11 clicks.

But wait? Why is the word count different from the table above? Oathbringer is 455,511 here but 458,430 in Microsoft Word. Frankly, I have no idea. Different programs count words differently, for example, one might count "twenty-three" as one word while the other might count it as two words. If you prefer the Microsoft Word Word Count, you can convert to docx instead of epub. But this means you will have to open up the files one by one or try and get someone to write a script.

In any case, this is definitely 100,000% more accurate than using the page count on Amazon to determine word count. As for where the 250 words per page figure came from, I don't really know. 250 words per page was a [shortcut used for typewritten manuscripts back in the day when word processors did not exist](http://answers.google.com/answers/threadview?id=608972){:target="_blank"}. Nowadays, you can still get approximately 250 words per page if you have 25 lines of Courier New 12pt text in a page. As far as I know, Amazon has never stated 250 word per page. Maybe it is a kind of [Mandela Effect](https://www.verywellmind.com/what-is-the-mandela-effect-4589394){:target="_blank"}?