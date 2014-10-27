# College 5 - From Objects to Data

Within topic of transformations. 

## From fiction to data to narrative

Applying Ben Fry to actual research. How do you go trough his steps. Except of visualisation. How do we show numbers and evaluate what you've done. Tables. 

The riddle of literary quality. Working with fiction, transforming it to information. What do you do with the data is important. Trough trial and error they've seen how important narrative. 

Linking this to computers. Why are we doing computational analysis. Is it because it peaks your interest? Of is it something else what peaks your interest. You could use it. 

In practice it something different. 
- Because you can't get arround it
- Because you can
- Because you should (Moretti)
- Because that's where the money's at
- Because ...

You miss out on alot of data is you don't use computers. You need a interest of yourself though. You can get money alot easier to get money if you do something with computers. 

David Hoover. Computational analysis on literary. Text analysis.  How you can actualy computationally seperate speach for other parts of the texts. You can give the computer a sentence and ask whom said it. Henry James novel could do it, but another writer coudn't be detected. With the computational method there suddenly was a method that could show this. You could distinguish better novels from lesser ones. He was in a commity for the the the riddle of literary quality.

Something that tickles your interest could someday be usefull. Steve Jobs kaligrafy example. 

The Riddle of Literary Quality. Two professors, two phd's and a programmer. Rather big. Goals:
1. Textual communalities (X-factors)
2. In recent Dutch novels
3. with similar appreciation

There is a big debate about literature. Publishers. Atlas, Bezige Bij. These actually decide what literary quality constitutes. You will assume its of a certain quality. Long has been thought this is the only factor in literary quality. By curation and communication. Chick-lit we assume the opposite. But there should be something in the text according to Koolen. But what in the text determines the importance? They are not going to decide what is literary however. They let the public decide. (problematic?)

Recent Duch novels: corpus. 2007-2012. Most often bought and borrowed. Originally Dutch or translated into Dutch. Epub or pdf-format. 400 for a decent enough number for people to have read them, and still be able to generalise. 

Following trends, the research cannot prove that only the text is literary. Textual communalities. Its also detemined by alot of social factors.

The texts are online, but it should be done in a nice way. There is are a lot of rights involved. There are a lot of different factors involved too. Formats include all kinds of weird stuff. Some use weird whitespace characters. Others don't use tagging. 

Reader survey. How literary or how good they are. There is a difference, people can love it but does not have to be literary. People choose good books, the cloud is far literary and good. There term literary is not defined. Style is often mentioned when asked.

(it seems there are alot of floating terms. Good / Bad. Literary, not literary.)

Social factors are still very important. Top 10 has male writers, bottom 10 female authors. 50 Shades of Grey is down there, people wanted to reply even if they hadn't read it. They gave it a bad mark. Social factors are really important in rating books. 

## Textual commonalities

- Basic sentence structures. Complex or compound sentences. Sentences connected with and or but. Its a lot of work to get there though. 

Themes are interesting too. Difficult words you can count. Themes however are more interesting. Topic modelling. Its hard to make sense of it though. Looking at full novels won't get you anything. It won't tell you anything. Medical, Maritine. Finding themes on a smaller scale might be interesting though. 

Narrative structure is also quite interesting. You have to think about when and when not to use a computer.

Big Data. A few books would not be big data, but if you analyse on the sub-level level it would choke google servers. 

## PAUZE --

Point A -> B. Ideally narritive its a straight line. But its not that straight. 32 novels. 16 novels that were literary, and 16 that were not. 32 Novels that were not necessairy part of the corpus. Toy corpus. Its not very hard to tell which is chicklit and literary.

You can look at sentence structure. Characters are really imporatant. It hasn't been researched to much, some feminist do study the display though. There are certain notions about chicklit that still need proof, that are analysed in theory but still need more. It not black and white. 

Ben Fry has been used to structure the project. What do the descriptions of physical appearance look like in both types of novels.? What are the differences between the genres? It cannot be awnsered straight away. It's broad, because you never know what you're going to get. You adapt it to the research, this in contraire to a more hermeutical approaches.

Two books where tagged from cover to cover. Every sentence with a discription in it was tagged. Pre-question. How well can we find such questions. Two methods. Literary-syntactic queries, you have a pattern that you translate to computer language. XML trees where used. You can use syntactic information. They wanted to have syntactic information, put in Alpino, to get the sentence structure. XML is a markup language where you can tag within, Apino used it. You can traverse them quite easily. XPath is a language where you can ask the questions in. 

Physical appearance. Not something simple however. What characters look like? Modifying perpositional phrase that contains an adjective and a noun from the lexicon. 

Preposition phrase, something that sais something about the object. Result = person + "something" + lexicon match ("hair, feet, etc.").

Machinelearning was also used. In there you have your set of data. You just use the plain text files. The computer usally don't make a straight division. Which sentences contain discriptions? 2-6% contain discriptions. We dont have numbers, we have text. The computer can't easily calculate with words. It converts the words into numbers. If the question is distinct enough, the computer can distinguishs them. Word weight and bigrams where used also, didn't change. Transformation of words to numbers.

Computers can distingisch authors. "the in a" function words determines author, content words don't. It's something authors don't think about that much. 

There are alot of steps between the actual the result and the representation of it. Evaluations can be manipulated quite easy.  It really important to show your calculation methods. 

The computer coudn't distinguise descritive sentences easily. You can however say something about the chick lit and literary novels to awnser the research question. Chicklit is usually obsessed with body, bodily features. You can detect them on that. But liturature is scruitinised on all meaningfull levels. Chick-lit has never been analysed on a literary level. You could look at it now. Literary novels contain more! physical descriptions. Why do you get more? 

The machine learning and the queries are used together too. If you do that you get a higher extraction for the chick-lit novels. What does it mean that you get a higher extraction in the chick-lit. Possibly simple texts, but might also have to do with standardisation. 

Literary novels may be more concerned with physical appearance than assumed. Chick-lit novels contain more formulaic language. Eyes were also more important, formula in the chicklit. One book did look at sentence structure in chicklit, bodyparts are more important in literature. You do not know what the number is saying, you really need to carefull examine it. 

Disappointing results could be viewed as result. Expected distinguisable results end up being not so much. The ones that are not are on the lines and may be the most interesting. 

For whom its interesting, its not nearly acceptable for computer sciences, and also not literary, only in a small corner. 
