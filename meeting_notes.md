## CC@Home: Library Carpentry Wikidata lesson sprint
## 2020-07-14, 8:00 UTC

### Roll call + Check in:

Niklas zimmer / niklas.zimmer@uct.ac.za / he, him, his / @niklaszimmer
Wangui Mwangi / mwangiwangui25@gmail.com/ she and her/ @essmarie_1
Serah Rono / serah@carpentries.org / she, her, hers / @serahrono
Till Sauerwein / sauerwein@zbmed.de / he / @TillSauerwein
Rabea Müller / mueller@zbmed.de / she/her / @MueRabea
Konrad Förstner / foerstner@zbmed.de, him/her | @konradfoerstner
Chris Erdmann / erdmannc@renci.org, he, him, his / @libcce

### Notes:
Episodes 4 and 6 need to be worked on
Episodes 1,2,3 and 5 are almost done. Proofreading?

- Add Episode/Set-Up disclaimer that attendees need to make a Wikidata account at least 4(!!) Days in advance. Editing on Wikidata is limited for new user accounts. Caution: Multiple accounts might not be possilbe to be created from the same IP

### History:
discussions around this lesson started in november 2018 in Berkeley at a Wikicite conference
the lesson was then set up, but active work started once Rabea came on board
it is now in a 'ready to use' state

### Quick overview
Human and machine readable knowledge base
coming from Wikimedia universe, all content is open (CC-BY, CC-0 license) that is editable
editing and reuse is relatively easy for all, by design
unmaintained versions of wikipedia, i.e. those run by smaller communities (languages not used by many), ---- (ask Konrad to expound here)

### TODO suggestions:
Niklas
Maps out of copyright, video, audio … unpublished material, possibly with links to published materials or other kinds of ‘public’ ‘products’
Also as a registry of identifiers for authors across the institution, so we don’t keep duplicating ‘person’ in our various databases
One example where we focus on building academic profiles: Zimmer, Niklas; Muftic, Sanjin; Slingsby, Thomas (2020): Setting up and linking your academic profiles online. University of Cape Town. Presentation. https://doi.org/10.25375/uct.9725393.v1
- add motivation and why to use wikidata as an librarian in episode
- add registration for participants two weeks earlier
- WikiProject: Women in Redhttps://blog.wikimedia.org/2018/03/29/increasing-visibility-women-with-wikidata/ 
- add as game later on (episode 5, after introduction into querying)
-source for getting DOIS
- find your own preferred example or you use or example
- PLOS ONE as example
- using test instance for editing Mae Jemison 
- use the initials of the participants to keep them different
- and then also use for reference example
- give link to the participants and tell them to add birth with reference
- https://www.britannica.com/biography/Mae-Jemison for searching on reference
# **2019-04-01 Library Carpentry - Wikidata Lesson Sprint**

* **Aim of the Sprint:**
     * Further develop the lesson in detail
    * The previous work of the **last session** that took place on  2019-03-12 can be found at https://hackmd.io/T9E1Q-QZRdu-pN8ubyi4-w?both#. 
    The work included developping the LC wikidata lesson GitHub page: https://github.com/LibraryCarpentry/lc-wikidata


* **Participants** (please add your name):
    * Konrad Förstner (foerstner@zbmed.de)
    * Till Sauerwein (sauerwein@zbmed.de)
    * Muhammad Elhossary (elhossary@zbmed.de)
    * Alexandra Provo (alexandra.provo@nyu.edu)
    * Mairelys Lemus-Rojas (mlemusro@iupui.edu)

* **Data model - Marie Curie**
Spanish - https://commons.wikimedia.org/wiki/File:Datamodel_in_Wikidata_Marie_Curie_es.svg
English - https://commons.wikimedia.org/wiki/File:Datamodel_in_Wikidata_Marie_Curie_en.svg

# **2019-01-21 Library Carpentry - Wikidata Lesson Sprint**

* **Participants** (please add your name):
    * Konrad Förstner (foerstner@zbmed.de)
    * Till Sauerwein (sauerwein@zbmed.de)
    * Muhammad Elhossary (elhossary@zbmed.de)

* We will work separately as small teams on the 6 modules below. The modules were first transcribed at https://www.wikidata.org/wiki/Wikidata:Wikidata_curricula#Wikidata_for_librarians. 

    An extended version with learning outcomes can be found     further below.

* Please **assign yourself to one of the 6 modules** below by adding your name after the module headline and if neccesary a link to a zoom/hangouts/skype/* meeting so that others can join your work group.
An extended version with learning outcomes can be found     further below.
	1. What is Wikidata?
	2. Structure/Conceptual foundation/Mechanics 
	3. Intro to editing
	4. Creating new items
	5. Intro to querying
	6. Advanced

### Extended version with learning outcomes 
(taken from https://etherpad.wikimedia.org/p/WikiCite18Day3Tamalpais3B):

# Todo:
*  Add participants of the WikiCite session to https://github.com/LibraryCarpentry/lc-wikidata/blob/gh-pages/AUTHORS after asking for their permission (Konrad)
*  Describe pro and cons of first editing an existing item vs. creating a new item (Till)
    * creating a new item and editing it:  
        * pros:
            *  more stable solution
            *  not overwelming by too much information
            *  same starting point for everbody
            *  Instructor does not have to prepare
        * cons:
    * editing an already existing item:
        * cons:
            * can be overwhelming if there are already a lot of items
# Current working version

## Module 0: Requirements ##
- Proper internet connection

##  Module 1: What is Wikidata? ##

### Learning outcomes ###
* Feel comfortable describing Wikidata to colleagues
* Understand how Wikidata relates to other Wikimedia projects
* Understand why linked open data is important in my work as a cataloging or teaching librarian

### 1.1 Intro interface ###

- Homepage - Screenshot and link to page (Participants should visit the page: https://www.wikidata.org/wiki/Wikidata:Main_Page)
- Earth (Q2) - Screenshot and link to page (Participants should visit the page https://www.wikidata.org/wiki/Q2)
- Description of Earth (Q2) as an example for an entry
    - Title - Earth (Q2)
    - What does "Q2"?
    - What is an item https://www.wikidata.org/wiki/Help:Items
        - Has 
            - unique identifier (Q + a number)
            - label 
            - description
            - aliases
    - "Statement" section
        - What is a statement?
            - Has
                - property (P + a number)
                - value
                - qualifier (optional)
                - references (optional)
            - is a so called triple which will be explained later
    - As you can see a property can have multiple statements for one property; for example "Population"; they are specified by "qualifiers" like point in time; an can references e.g. population at the 5 January 2016 has the reference http://www.worldometers.info/world-population/ as source.
    - Usually pages can be edited by anyonce; click the pen on the upper-right; Q2 - Earth is semi-protected (as it is very important); don't worry you made a mistake, you can alway go back in history
    - "View history" - more later
    - "Log in" and other things for registered users
- CC0 
- Further Links
    - https://commons.wikimedia.org/wiki/File:Wikidata-in-brief-1.0.pdf
        
        - https://www.wikidata.org/wiki/Wikidata:Introduction#/media/File:Datamodel_in_Wikidata.svg
        - 

### 1.2 Play games to open ###

- Visit random items: https://www.wikidata.org/wiki/Special:Random
- TODO - more games needed

### 1.3 Relationship with other wiki projects ###
- Link from Wikipedia to Wikidata
    - e.g. https://en.wikipedia.org/wiki/On_the_Origin_of_Species
        - => Follow the link "Wikidata item"
        - => https://www.wikidata.org/wiki/Q20124
        - => link to WikiCommons and WikiSource
-  Link items to other wikis either added by humans or bot

## Module 2: Structure/Conceptual foundation/Mechanics ##

DISCUSSION: 
* There are already clashes with the previous module
* Option 1 set focus or on the usage of it for librarians
* Option 2: merge this completely into Module 1
* Option 3: Put to the end (later module)

### Learning outcomes ###
* Identify components of a Wikidata item page (DONE ABOVE)
* Know where to find information on navigating Wikidata (AIM NOT CLEAR)
* Define what's different about open data and why it's important (DIFFERENT TO WHAT?)
* Understand what a triple is, and relate structure of a Wikidata statement to traditional metadata field structure
* How linked data can create more context for patrons/users in library catalogs
* How linked data can improve recall in library catalogs


### 2.1 RDF triples

- RDF vs. relational database

- https://en.wikipedia.org/wiki/Semantic_triple

### 2.2 Semantic web/structured data

- https://lod-cloud.net/


### 2.3 Wikidata one pager
- https://commons.wikimedia.org/wiki/File:Wikidata-in-brief-1.0.pdf

### 2.4 How Wikidata compares with other data sets 

## Module 3: Intro to editing ##

### Learning outcomes ###
* Be able to create and edit a Wikidata entry
* Understand properties and relations, and where to find lists of approved properties and relations
* Be able to add new statements that link to other items
* Understand property constraints

        
### 3.1 Create and edit an new item in the test instance ###

Here we will work in the test instance of Wikidata so you will not break anything. Also keep in mind that the editing history is kept in Wikidata so error can also be easily fixed there:

#### 3.1.1 Create a new item ####

- Goto https://test.wikidata.org/
- Click "Create a new Item"
- Fill the form 
    - Language:
    - Label
    - Description
    - Aliases
- Click "Create"

#### 3.1.2 Add statements ####

- Data types: 
    - String
    - Properties
    - Quantity
    - Time
    - URL
    - And many more https://www.wikidata.org/wiki/Help:Data_type

- Click add statement
- Fill a property and a values

- Some suggestions for statements:
    - "instance of" (P82) - "book", "scholarly article"
    -  "date of publication" (P151) 

Have a look again at Origin of Species to get inspiration: https://www.wikidata.org/wiki/Q20124

### 3.4 Community norms [examples of how other libraries have used?] ###

## Module 4: Advanced editing ##

### Learning outcomes ###

* Use some tools for editing, e.g. TABernacle, Wikidata Games, QuickStatements, Source MetaData or Author Disambiguator/Author resolver
* Understand community norms around WikiData and why they're important
* Be confortable with collaborative, decentralized data creation e.g. carpentry participants should be able to identify gaps in Wikidata that could be filled not just by the participants themselves (and at the event) but by their community more broadly, or specific actors within it
* Add references appropriately
* Be able to compare process of editing to process of editing/adding metadata in existing library information systems (ILS, IR)...?
* Understanding Identifiers
* Connect to how this improves things for our patrons/users... 

### 4.1 References ###

- Support a statement by reference
- TODO - find example; Backup solution use the "origin of species example"

### 4.2 Citations link in wikidata ###
        
Example of a scholorly article with citations: https://www.wikidata.org/wiki/Q52641751

- some notes regarding the "cites" statement 

### 4.3 Norms ###

### 4.4 Finding stable identifiers (???) ###
        
## Module 5: Introduction to querying ##

### Learning outcomes ###
* Understand what a query language is, and how SPARQL differs from, say, SQL
* Be able to use SPARQL to query WikiData
* Potentially be able to use a tool like TABernacle (sp?) to edit based on a query?
* Have a cursory knowledge of the plethora of Wikidata querying tools (and how they can be used by librarians)
* Understand purpose and potential usefulness of maintenance queries for identifying missing information
* Practice creating maintenance queries

### 5.1 Wikidata Query Service (SPARQL) ###

* Query syntax
* What are Prefixes?


### 5.2 Try examples (research published that week?) ###


### further links ###
- https://commons.wikimedia.org/wiki/File:Wikidata_Query_Service_in_Brief.pdf
        
## Module 6: Advanced bulk updating, bots ##

### Learning outcomes ###
* Understand how to run a bulk import into Wikidata
* practice using quickstatements? (module 3 already includes QuickStatements)
* Be familiar with the tools used for bulk edits and imports 
* Tools for bulk upload: - Quick statements (https://www.wikidata.org/wiki/Help:QuickStatements)

* Connect bulk import possibilities to cataloging and digital science/archive projects?

* Understand how to write a good queries in terms of performance

