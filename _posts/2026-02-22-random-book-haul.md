---
layout: post
title: "Random Book Hauls in the age of AI"
date: 2026-02-22 01:00
author: Zed Dee
comments: true
---

Back in 2021, I could actually randomly browse through all the new sci-fi and fantasy releases for a certain month and actually find some great reads this way. Unfortunately, this is no longer possible as the number of new releases each month overwhelm even Amazon's page rendering algorithm. At 16 books per page, and page 400 being the maximum, Amazon can only display a theoretical maximum of 6400 books when filtering by publication month. But there were more than 10,000 new sci-fi and fantasy releases in January 2026 alone!

So, on Feb 21 2026, I searched for "horror", filtered to last 30 days, sorted by publication date, and had a go. I found a book that I liked on the first page, bought it, finished it, looked at the author's other books, and noticed a disturbing pattern. The author had published 3 books in the span of 2 months, and all the covers were template covers, just text with no graphics.

See, back in 2021, I had decided to not judge a book by its cover. This was based on the assumption that all books were written by humans, and being a good writer had nothing to do with being a good graphic designer. But I realise now that the situation has flipped around. I should definitely judge a book by its cover, especially low effort template covers, because it now means that the "author" was too lazy to even type a prompt into an image generator.

So I returned the book. I talked to a Customer Service Representative and told them that I had bought the book expecting to read human written content, but gowinston.ai and originality.ai had detected 100% AI. This, combined with the fact that the author had published 3 books in 2 months, and the low-effort covers, made it likely that it was AI-generated. I told the CSR that I wasn't sure, but since KDP has a AI-generated checkbox, I wanted a refund if the book was AI-generated. The CSR refunded the book. But this did not confirm anything. Maybe it's their policy to be generous on refunds.

But the point is that I could not tell that it was AI generated. Maybe it was the heavy noir metaphors. I perhaps should have picked up on it when "whisper" had been used in a metaphor for the umpteenth time, but I had thought that it was just badly edited. 

Or maybe it was written by a human after all?

So, after asking Claude to code a [Chrome extension](https://github.com/zeddeecee/amazonscraper){:target="_blank"} that would scrape book details from Amazon, on Feb 22 2026, I searched again for horror books, passed the output of the extension to NotebookLM, and asked it to filter out books according to these criteria:

1. Have typos or grammar mistakes in description or title
2. Is a public domain work
3. Is obviously not licensed by copyright holder (e.g Resident Evil stories not published by Capcom)
4. Is published by a big publisher (Big 5)
5. Is a short story collection or a short story
6. Is not first in a series (standalone books are okay)
7. Is non-fiction
8. Is not a novel (no comics and colouring books etc...)

From 80 books, 2 were above $9.99, 66 failed one way or another, and only 12 were left.

## [Arkhé Academy: Awakening](https://www.amazon.com/dp/B0GNK4PG36){:target="_blank"}

Since I'm judging books by the cover now, this does not pass. Author only has 1 book, but no bio and no photo. So, just to be sure, I typed in the first 2 paragraphs into originality.ai.

> Her cries had been deafening once. They bounced off the steel walls of the fire station's surrender box, raw and endless, the kind of sound that lived under your skin. Thirteen days old and left in the dark.
>
> The box shut her in with the smell of smoke that never quite died, mixed with the sting of disinfectant. She was wrapped in a black leather jacket, one that carried more than the worries of whoever left it behind. The sleeves were burned and curled, the wrists scorched. It smelled of sulfur and something older, something that didn't belong to this world. Even as a baby, part of her must have known it wasn't just a jacket. It was a warning.

Result? 100% confident it's AI.

## [Pantheon of the Damned: A Dark Fantasy Novel](https://www.amazon.com/dp/B0GCDHBL1V){:target="_blank"}

Author photo looks AI generated. Also, author apparently also has B.A. in the Arts.

## [The Cajun Curse](https://www.amazon.com/dp/B0G8484K3F){:target="_blank"}

Author photo looks AI generated, at the very least it was run through a filter. Anyway, I typed like two paragraphs of the book's sample into originality.ai and it said it was 100% AI.

## [The House That Waits: A Haunted House Psychological Horror Novel](https://www.amazon.com/dp/B0GPLSMC1H){:target="_blank"}

Between May 22 2025 and Feb 21 2026, author published 23 books. That's 2.5 books per month.

## [The Last Thing She Saw (Extreme Horror Collection)](https://www.amazon.com/dp/B0GPKDRNZW){:target="_blank"} and [Spin The Killer (Extreme Horror Collection)](https://www.amazon.com/dp/B0GP8WN8DH){:target="_blank"}

Wow, 2 books on the same day. Apparently, on his oldest book that was published in Aug 21 2025, the author under "Follow the Author" is Vijay Martis instead of Killa Sparrow, and Vijay Martis has 316 books.

## [The Hellier Incident: A Sci-Fi Horror Novel](https://www.amazon.com/dp/B0GJLTZPVF){:target="_blank"}

This one is 100% real.

> On the evening of Wednesday, July 2nd, Dan Wilmot stepped out onto the porch of his white-painted house. As he adjusted his belt to ease the pressure of his recent meal, he glanced at the distant flashes illuminating the night sky. Sheltered under the porch roof, he took a few steps forward and swept his gaze across the panoramic expanse of sky before him. Dark clusters of clouds pulsed with light from within. Summer thunderstorms were no stranger to the area, but this one. still gathering strength, promised to be more spectacular than most.

I know because there's a typo in the first paragraph, a period that should be a comma. But it's also why I'm passing on it, because of the typo in the first paragraph.

## [Revenge of the Wolf Emperor: Godfall Apocalypse Book 1](https://www.amazon.com/dp/B0G64KQXK2){:target="_blank"}

Author published 2 Christian self help books, first one on Jan 21 2026, second one on Feb 5 2026, then this one on Feb 20 2026. That's 3 books per month!

## [Jeremy: A Horrible Truth (Jeremy : A Horrible Truth Book 1)](https://www.amazon.com/dp/B0GLHGN7W3){:target="_blank"}

Author has published some self-help books and then some sci-fi stuff. But the text in the novel has the classic AI tell.

> Some houses remember.
>
> They remember laughter echoing down hallways long after the sound died.
>
> They remember footsteps that never leave.
>
> They remember pain—especially pain that had nowhere to go.
>
> The house on Maple Hollow Road was built with a basement meant for storage. Shelves. Boxes. Christmas decorations wrapped in yellowing paper. It was never meant to be a grave. Never meant to swallow a child whole and keep him there, pressed beneath concrete and silence.
>
> But houses don't choose what they become.
>
> They only absorb.
>
> Jeremy didn't die screaming. Not at first.
>
> What killed him wasn't just the acid that burned through his skull, or the darkness that swallowed him when the door closed. It was the moment he realized the woman who saved him never intended to keep him alive.

9. [The Ninth Layer](https://www.amazon.com/dp/B0GN1XPZT2){:target="_blank"}

No tells in author bio and past publications, except for maybe some weird chest-beating about him being the best thriller author of 2025. Originality.ai is 100% confident that the first few paragraphs in this book are AI generated though.

10. [THE 2:13 AM BROADCAST: An Analog Horror Novel](https://www.amazon.com/dp/B0GPG6YKXJ){:target="_blank"}

Cover fails my smell test. Also look at these covers for his previous books.

![Stupid covers](/content/images/20260222-RandomBookHaul01.jpg)

No Algorithm?!

12. [The Watcher of Hollow Creek: A Small-Town Psychological Horror](https://www.amazon.com/dp/B0GP9NV1CV){:target="_blank"}

Author has published 36 books since Nov 18 2025. That's 9 books a month! But take a closer look. 25 books were published in February alone!

---

Out of 12 books, only 1 was written by a human. If this isn't fucked up, I don't know what is.