---
title: What is Wikidata?
teaching: 20
exercises: 10
---

::::::::::::::::::::::::::::::::::::::: objectives

- Feel comfortable describing Wikidata to colleagues.
- Learn about Wikimedia projects (e.g. Wikipedia, WikiCommons) and how Wikidata is related to them.
- Know why linked open data is important to librarians.
- Be able to identify components of a Wikidata item page, how Wikidata is organized and how to navigate a Wikidata item.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What is Wikidata?
- How does the Wikidata interface look?
- How is Wikidata linked to other Wiki projects?
- What are Items and Statements?

::::::::::::::::::::::::::::::::::::::::::::::::::

## What is Wikidata?

Wikidata [describes itself](https://www.wikidata.org/wiki/Wikidata:Main_Page) as "a free and open knowledge base that can be read and edited by both humans and machines." 

Most users will be familiar with [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Introduction), the "free encyclopedia, written collaboratively by the people who use it. It is a special type of website designed to make collaboration easy, called a wiki. Many people are constantly improving Wikipedia, making thousands of changes per hour. All of these changes are recorded in article histories and recent changes."

Wikidata uses the same speed and similar collaborative editing platform, but for data. Wikidata functions as the central database for a variety of Wiki projects, including Wikipedia, Wiktionary, and Wikisource, among others.

Wikidata contains various data types (e.g. text, images, quantities, coordinates, geographic shapes, dates). The data can be viewed in a web browser, but it can also be queried via a query interface called SPARQL, which we will cover later in this lesson. Data on Wikidata is published under the Creative Commons Public Domain 1.0 license. Thus, the data can be modified, copied, and distributed without permission.

Wikidata also contains authority files, bibliographic data, and other content normally managed in library databases.

Importantly, Wikidata can be understood as linked open data, which can be  [connected](https://www.wikidata.org/wiki/Wikidata:Data_access#How_can_I_get_data_out_of_Wikidata?) to other open data sets on the web.

## Motivation and "Why should I use Wikidata"

Wikidata has many features that make it of interest to librarians and knowledge management, including:

1. **Knowledge Integration and Access:** Wikidata offers an open and structured way to interlink various identifiers (like ORCID, GND, or VIAF). This is essential for librarians who manage resources and need to ensure that different systems and databases can communicate with each other seamlessly.

2. **Authority Control:** Librarians often work with authority files like GND or VIAF to ensure consistent naming conventions. Wikidata helps to map and retrieve these identifiers, making cataloging more efficient.

3. **Global and Collaborative Nature:** Wikidata is a collaborative platform where librarians can contribute and maintain data, ensuring that their records stay relevant and up to date within a global information network.

4. **Real-World Examples:**
  a. *Scholia*: A tool built on top of Wikidata that visualizes scholarly profiles and research outputs, showing the impact of Wikidata in academic and research contexts. Librarians can showcase Scholia as a tangible example of how data in Wikidata is used for research and scholarship.
  b. *Crosswalks between systems*: Wikidata’s ability to link various identifiers (e.g., connecting ORCID to GND or VIAF) is beneficial for cross-referencing and data cleaning in library management systems.

## 1\.1 Intro interface

This section of the lesson introduces the Wikidata interface as it can be seen in a web browser.
Let's see if we as humans can simply read the data on Wikidata:

- Explore a Wikidata Item page

  - Start by going to the [Wikidata Main Page](https://www.wikidata.org/wiki/Wikidata:Main_Page) by typing "www.wikidata.org" into your browser. You will see something like this:
  
  ![](fig/Wikidata_Main_Page.png){alt='Screenshot of the Wikidata main page displaying in a web browser'}  
  *Screenshot of [Wikidata Main Page](https://www.wikidata.org/wiki/Wikidata:Main_Page)*
  
  - Now go to the search bar in the top right corner and enter "british library". This will give you a list with search results. Click the entry that says: "British Library (Q23308) national library of the United Kingdom". Now you should see the british library's item page:
    [https://www.wikidata.org/wiki/Q23308](https://www.wikidata.org/wiki/Q23308)
  
  - Let us explore the item *British Library (Q23308)*. The top part of the item page identifies the item. It displays:
    
    - unique identifier (constructed as the capital letter followed by one or more numbers)
    - label
    - description
    - aliases
  
  - Lower on the page is a *statements* section, which shows relationships that have been asserted about the item. A statement has:
    
    - property (constructed as the capital letter P followed by one or more numbers)
    - value
    - qualifier (optional)
    - references (optional)
    - can also be called a "triple," which will be explained later
    - As you can see, a property can have multiple values for one property; for example "member of"; and can be further specified by qualifiers (not shown on the item page for British Library).

- There are many special terms and definitions here, like statements, qualifiers and so on. Since many of these terms can be confusing, you may check [this overview graphic as a reference](https://upload.wikimedia.org/wikipedia/commons/a/ae/Datamodel_in_Wikidata.svg):

![](https://upload.wikimedia.org/wikipedia/commons/a/ae/Datamodel_in_Wikidata.svg){alt='Labeled display of a Wikidata item showing how elements like identifier, description, and staements may be displayed'}

- Most pages can be edited by anyone (note, however, that the British Library - Q23308 item is semi-protected). To edit an item, click the pen icon followed by the word "edit" in the upper-right are of the page. Don't worry if you made a mistake, you can always go back in an item's history and restore or undo changes.
  
  - "View history" - more later
  - "Log in" and other things for registered users

- All of Wikidata's data is published online under the [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/), which states:
"The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission." 
In other words, the data is openly licensed and reusable. Since Wikidata can also be linked to other data sources on the web, this means Wikidata is *linked open data*.

- Follow this link to view a pdf that offers a one-page overview of Wikidata (visual): [https://commons.wikimedia.org/wiki/File:Wikidata-in-brief-1.0.pdf](https://commons.wikimedia.org/wiki/File:Wikidata-in-brief-1.0.pdf)

## 1\.2 Play games to open

- Visit the Wikipedia page of the city you were born in two languages
  of you choice (you can choose different language version in the left
  side of a Wikipedia page) and look the size of the population. Are
  the numbers the same in the different language? Visit the item in
  Wikidata.

## 1\.3 Wikidata Item Eastereggs

While most of the Q identifiers are arbitrary numbers, there are a few that suggest some meaning or humor, such as:

- [Q1 - Universe](https://www.wikidata.org/wiki/Q1)
- [Q2 - Earth](https://www.wikidata.org/wiki/Q2)
- [Q3 - Life](https://www.wikidata.org/wiki/Q3)
- [Q4 - Death](https://www.wikidata.org/wiki/Q4)
- [Q5 - Human](https://www.wikidata.org/wiki/Q5)
- [Q13 - Fear of the number 13](https://www.wikidata.org/wiki/Q13)
- [Q24 - Jack Bauer](https://www.wikidata.org/wiki/Q24)
- [Q42 - Douglas Adams (The Hitchhiker's Guide to the Galaxy)](https://www.wikidata.org/wiki/Q42)
- [Q404 - HTTP 404](https://www.wikidata.org/wiki/Q404)
- [Q666 - Number of the beast](https://www.wikidata.org/wiki/Q666)
- [Q12345 - Count von Count, Character on Sesame Street](https://www.wikidata.org/wiki/Q12345)

## 1\.4 Linking Wikidata to other Wiki resources

- Link from Wikipedia to Wikidata
  - e.g. [https://en.wikipedia.org/wiki/On\_the\_Origin\_of\_Species](https://en.wikipedia.org/wiki/On_the_Origin_of_Species)
    - \=> Follow the link "Wikidata item" on the left side under "tools"
    - \=> [https://www.wikidata.org/wiki/Q20124](https://www.wikidata.org/wiki/Q20124)
    - \=> the Wikipedia article is linked on the Wikidata's item page. You can find it on the right side.
    - \=> link to WikiCommons and WikiSource

:::::::::::::::::::::::::::::::::::::::: keypoints

- Wikidata entities are known as Items, and each item is displayed on a page that is identified with the item's "Q" number
- Relationships between entities are known as Properties, and each property is identified with a "P" number
- Statements are assertions about items, which state relationships between items using wikidata properties.
- Statements are also known as "triples"

::::::::::::::::::::::::::::::::::::::::::::::::::
