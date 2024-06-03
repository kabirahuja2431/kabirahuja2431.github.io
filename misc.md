---
layout: default
title: "Miscellaneous"
permalink: "/misc/"
---

# Miscellaneous
Some of the activities that I feel provide a lot of meaning to me include reading fiction and watching films. With the fear of sounding too pretentious, I think film, literature and other art forms are incredibly important as they help our life experiences be less singular, make us see things from different perspectives, and let us ponder on ideas that would otherwise elude us. 

<!-- With sparing moments of inspirations I try to jot down my thoughts on films I saw or books I read, some of which you can find [here](/reviews/).  -->

Below, I list down some of my favorite books and films. The lists follow no particular order and are selected based on my personal experiences with them and not meant to provide any objective ranking.

**Favorite Books**:
- *Never Let Me Go* by Kazuo Ishiguro
- *One Hundred Years of Solitude* by Gabriel García Márquez
- *Midnight's Children* by Salman Rushdie
- *The Memory Police* by Yōko Ogawa
- *The Wind Up Bird Chronicle* by Haruki Murakami

**Favorite Films**:
- *Eternal Sunshine of The Spotless Mind* (2004) by Michel Gondry
- *Burning* (2018) by Lee Chang-dong
- *Secret Sunshine* (2007) by Lee Chang-dong
- *A Brighter Summer Day* (1991) by Edward Yang
- *In the Mood for Love* (2001) by Wong Kar-wai
- *Her* (2013) by Spike Jonze
- *Paris, Texas* (1984) by Wim Wenders
- *The Disciple* (2021) by Chaitanya Tamhane
- *Mulholland Drive* (2001) by David Lynch
- *I am Thinking of Ending Things* (2020) by Charlie Kaufman
- *Barry Lyndon* (1975) by Stanley Kubrik

<!-- Some of my amateur reviews of movies / books. Added here at a time of boosted self confidence, might disappear soon as I start finding them embarrasing again. -->

With sparing moments of inspirations I try to jot down my thoughts on films I saw or books I read, some of which you can find below. I am also fairly active on [Letterboxd](https://letterboxd.com/kabirahuja2431/) and [Goodreads](https://www.goodreads.com/user/show/109298324-kabir-ahuja).
{% assign reviews = site.reviews | sort: "date" | reverse   %}
{% for review in reviews %}
- **{{ review.date | date: "%B %d, %Y" }}**: [{{ review.title }}]({{ review.url }})
{% endfor %}