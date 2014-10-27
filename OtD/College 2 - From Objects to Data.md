# College 2 - From objects to Data

## Papers

Everything in English. 

Question from Honours studdent at DH course:
Did painters paint outdoors more after the invention of paint tubes? Its alot more portable. Is there a way do some digital research to shed light on this? How could you do this?

-> Quite a difficult question to anwser. 

## Fry's seven steps

He comes up with these seven steps. These are quite the same as doing research. But there is a step zero. What is your question? I many case you can't answer it completly, but it should be clear. Starting with that is the most important thing. What is what we want to know? How do we shed light on it? 

Then the hard part, how do we go from the question to the endproduct. We need to think about the steps and transform them into something. There is a relationship between thinking and doing. You have to critically analyse what you do. What does it accually say? The process is often non-linear. Alot of times the process is not linear. You keep jumping between the questions.

Today: aquiring data. A recipe, an algoritm. But today about the question and aquiring data. In the end we want something that we can look at and tells a story.

## Primitives

You want to use the primitives to something that sheds light on a question? Small things lead to impressive things. Every little things leads to something bigger.

- Unsworth:
Annotation, comparing, discovering, illustrating, representing, referring, sampling, selecting. 

- Bradley:
Annotating, collecting, filtering, selecting, structuring, transforming. 

- Fry
Acquiring, parsing, filtering, mining, representing, refinting, interacting.

All of these guys talk of small steps, that could be called primitives. Unix has them too. 

- Unix
curl, wget, grep, find, awk, sed, sort, uniq

These tools could lead be compared to the scientific primitives.  Are the concepts primitives at all? Parsing is a complex action.  This is a good way to illustrate what the computer can do for you.

Bradly: the small things build up to a big thing. You can build a cathedral with bricks. You want to build something that is impressive. Networktools help in the process, many people preforming many little task quickly add up to something big. 

Shirkey: cooperation without coordination. Tagging things. Nobody talks about the tagging. But data still grows systematicly. 

### Bradly 

Conduit model: we use our computer for browsing.
Transformation: searching and filter, your computer can do things for you. 
Markup models: add notes to tekst. Representing, parsing, linking. If you add alot of markup you add a extra layer to the tekst, and you claim ownership of it. There are alot primitives involved.
Object manipulation: more or less a combination model.

Normal notetaking and essays could also be considered as using these models.

Data-driven research is all over the place.

## Source Criticism

Aquiring data. You get your data from something. But what are you getting? If you have data from some API, you can say that is the source. But you can also look at the provider of the data: the NYT. What data did we get and what didn't we get? What's missing? Did we use the wrong method? Reflecting critically on it is important. 

Google Ngram viewer. Which uses the corpus of digital books that google has. You can see when which word was used. How frequent were they in literature? This gives us a idea of how popular the words were. Is this a representable corpus? Mabey. It's used for many a research. We know a little bit what the tool is right now. 

130 million books have been published, but google has 10% digitised. But how older it gets, the more OCR mistakes their are. Every one out of a 100 karacters is misread. Earlyer their are mistakes like 50%.  (How critical were they about data?) Most of their contracts are also with US universities. There is lots of stuff not in there. There are all kinds of biases you need to take in account. 

Joanne Guld studie the variant of "to walk" in Literature.  She had a list of verbs that were synonyms. Strolling jumped in popularity from 1800's. How do I find other variants of to walk?  She used close reading to characterise the findings. But in an update of the corpus... The pattern changed completely. You always need to be aware of this. You always have a limited sample available. It was probably an error in the OCR. (fstrolling is found before)

COHA is also another tool. Historical American texts. You can give alot more variation. This gives alot more control. You really need to think about selection and sampling. Sampling you can do random? How do you represent collection of materials.

## Aquiring data

How would you awnser the questing?
-- Context
- Geograpic spread
- Timeframe
- Price

-- Depiction
- Iconografy. Outdoor? 
- Size. (bigger or smaller)

-- Literature (external sources)
- Documentation about the invention?

-- Size 
- Different paintings
- Alot?
- From where? How do you build up a sample that is representative?

Was it the invention that made people go out, or the other way arround?

Building up the sample is extremely difficult. You need to think about it. 

How are the Humanities potrayed in the New York Times. What are we going to look for. How do you select your articles from the NYT. 

Is the keyword "Humanities" enough? Synonyms are needed. 

What used to be society is now culture, and the other way arround. Meanings shift. Humanities mean diffirent thing in diffirent timeframes. Which definition of humanities are we going to look at? You'll never get a perfect set though. Topic modelling? How do we represent the Humanities. Taxonomy.

! There is no standard way to do this. You need to explain your choices. 

You shoudn't use google stats to the same as the ngram viewer. 

# Pauze

Orbis.stanford.edu : Google maps for the Roman Times. The website tries to be as explicit as possible about the data. Uncetainties are shown.

Krantenviewer also does source critism. We need more of this source critism. 

There are several prepacked datasets. The use of API's is important. Gathering data trough crowdsourcing is important too.  The web is a good way to find data. Scraping is a method too. API's often limits you to metadata, or gives only snippet. Also the Rijksmuseum API's limit things. Scraping is a way arround it. It's frowned upon though. Wget, Heritrix, scrapy. 

Wget, limit its recursion... Dont download the whole web. -m sais don't go beyond the domain. -w is also important... Wait a while to download the next page, to save bandwidth.  	

Robot.txt tells you what you're allowed to do. You can download stuff you're not allowed to, but you're likely to be banned. Twitter is often being scraped. 

## Data Structures

If you use API's you often get back something like JSON. Rijksmuseum does this for instance. Also interesting, they opened up the rights issues. 

There is an insane ammount of API's. Echonest for spotify. 

The commandline is kind of an API. Similar to this.

Govangogh is one way to do crowdsourcies. You can never do it yourself. 

Mechanical Turk is a generical platform. Costs money though. Interesting way of getting data. Source critisism is important. What is the quality? You have to deal with variing levels of expertise. You get all kinds of spam... but the quality is accually really high. The people who go to these platfroms are quite qualified. 

Jumping arround betweens folders is that there are all kinds of data structures. Json is Tree. CSV/TSV is matrix, table. With the formats invites playfullness. Comparables with urls or directories.


Within JSON you can navigate with dot notation. Within XML you can navigatie with slash notation (like directory structure)	.

AWK is complicated; might look at tuturials in slides. 

Proposal has to have three parts. Week three discussion about it.  


