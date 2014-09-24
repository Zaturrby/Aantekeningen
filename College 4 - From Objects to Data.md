# College 4 - From Objects to Data

## Parsing Data and Evaluation

This is on of the most intrigueing paper for the discussion within Digital Humanities. Interesting paper on the collision between the sciences and the humanties. He also does a few research things. 

## Methodology 

Fishing expedition. He takes a play of shakespear and makes a graph of the people and movements. He fishes for interesting stuff. This is very unscientific. 

Potter: "got to the data only when one is testing a clearly stated hypothesis". 

Ramsay: "I tried to think of things that naturally form themselves into graph structures". - This is far more normal than Ramsay makes it appear. He started exploring. 

Research paradigms in sciences and humanties are different? Nonsense. Any methodology every invented has also been used in the humanities. - Rens Bod. With any paradigm you've to stick with it, otherwise your collegues won't accept it.

Ramsay's methodology is far more common, but it dubious, serendipity is the process. You employ a strategy that makes things become more likely. We started our scientific approach from there. 

(Why is this approach dubious? It's probably less so that going from a predefined interest.)

He build a tool: shakespear in a network. But it should be more generic. It should allow for interaction, zoming, refining and filtering. It should require choices, how much do you need to make? What do you chose, is a part of the island, the same part as another identical identification? You need to metion the choice and explain it. 

Network tools are nice. Gephi. visualisation tool. You can quickly get a visual overview. It might bring out different insights that an long list of text. You can spot something interesting, but you'll have to lookup what makes it look like this. There also people who take this as an endresults. Visualising these have a few best practices. 

Another thing that Ramsey mentions are algorithm. The scripts we write are a recipe for getting for a -> b. These could be seen as algorithms. 

Titiaan was known for using a particular color red, titiaan red. Now we have alot of his images digitally. But he didn't. Now we have a hypothesis and evidence contradict each other. But this isn't really what we're about. Providing interesting interpretation is much more interesting. We should be constantly interpreting, this just allows us to interpret in a different way.

Data mining. Google. They are very good in it. They have alot of data, so they can spot alot of interesting patterns. There's bound to be an interesting pattern in data. But how do you find it? You need to tools to find them. It's a lot of guessing. The practice of data mining seems to be very close to what the humanities are doing, searching, interpreting. 

Ramsey finds some strange things. All the comedy's from Shakespeare can be grouped together. Its quite easy, less than 9,5 locations. We all know it probably not that simple, but it's interesting all the same. Which characteristics are linked to genre. You can catogorise things differently. Do these low level features have something to do with the way we interpret the genre. We don't really know how people do it, but there seems to be some level of agreement. 

## Parsing

So we have our data. But we have to segment in units that are usefull to use. In our case its easy, because the data is highly structured. But if you look at data from the web it's not that nicely structured. How do you get rid of all the overhead? You need to do alot of steps and argue wether they produce the right result. These meaningfull units might also change while you're buzy. You need to interpret alot, and use tools.

Parsing != Searching (filtering). Parsing selects the meaningfull units in a dataset, searching is different just shows a pattern in a mess.

Parsing is also done in traditional humanities research. You focus on specific aspects or you chosose specific persepectives. But are these a form of parsing or filtering? These primitive are not only digital. Digital just explicates things.

Representation. How do you identify an object?
- Text -> phrases, cencepts, themes, motifs.
- Films -> Scenes?
- regions, figures, colours. 

A meaningfull unit. You could use the analogy of scenes in films. Structure your data. Images are alot harder. Because building a tool might be too hard, human powered might be easyer.

Parsing Webdata. It's quite hard. You have to get rid of alot of stuff.

## Evaluation

Its very little discussed in Digital Humanities. It needs to be had in a structured way, it needs to be done. We're getting from a to b. But how accurate is it what we do? It's an important thing to realise. How often does it correctly identify the meaningfull unit? What margins are acceptable. Depends of the goal of data. 

It's also prevalent in traditional research, what is the margin of error there? Humans make mistakes too. Shouldn't we have standard defined. Size of the community, peer review. How could you figure your error out? You can take a sample and do it by hand. Manual Check or eyballing.

Quantative indicatiors of accuracy. 
Precision: Is you filter correct, do you select the right meaningfull unit.
Recall: Is the parsing correctly. 

## Topic modelling

## Beyond text

Can you find patterns in musical genres? What cap do you find? You can measure the gap between notes. Do it tell something about the genre? A simple hypotheses is that you find bigger gaps in Jazz. It's a example of parsing, because you don't know the melody anymore, but only the jumps between them. 

Mediamill. Concept detection. It trains itself. Football for instance is easy. Big green field with a blob going over the screen. Another example like Arafat was less succesfull, wassingcloth was also identified as him.

How do you make a list of tems to look for. How do you model a topic in words? Now we're getting in statistics. The thing is that this is really popular. It often makes little sense. But it shows nice results. What you do is that you use the statistics how often particular words are just to identify a topic. It uses statistics to go to a particular meaning. Its a hotly debated topic, as it counts, which is not the same as how we attribute meaning. 

How could we identify paintings that are painted outside. Can you look at the distributions of color? (You could perhaps identify a landscape, but not its place of painting). 

Difficult terms. Cooccurance. In articles about tour the france words like bicycle are not that uncommom, aswell as doping. They are very connected. If you have an article on the rising price on gass, the word bicycle is probably much more uncommon. You have a whole lot of articles, documents. Each is a bowl of words. Cooccurance, if one occurs the other probably also occurs. 

The models do a probability distribution. Some have a high and some a low probability. (how does this evolve over time?) (its a tool and a study itself!) Two models of doing topic modelling: LSI, LDA. 

## Projects

Tool: MALLET. Applied to a diary. Its a very inexact science and much debated. You often get interesting patterns though. Probably closer than we'd care to admit. 

Applied to 1860 America. Slavery, they see a jump in January, when there were slavemarkets. 

Sometimes it shows patterns that we do not know. To what extent are things a pattern.

Slides have a few tutorials on topic modelling. Started in the domain of search-engines, and those are very technical. These a less so. 

Tunes and Tales project. How particular elements of folk tales are transmitted orally. Look at the pattern over time and geograpic location. How did they spread. The same is done with folksongs. 

### Interpretation

You really need to know the corpus you're working with. If you arent an initiate in the field you have no clue wether the topics make sense. What do these things mean? You see alot of people making graphs, do they have a notion of what they're doing? It's not too hard, but you do need to study it a bit. The topics that seem to make the most sense are the incoherent things. There is a strong relation with statistics and meaning, but not completly. Topic models will never proof stuff, but it will show interesting patterns. Statistics often gives meaning that we don't know how to place.

Certain topics have a high probability, in other ones the probability between words is low. You need to check wether things are more sensible.

There is a couple of guidelines, but there are not many guidelines. If you've fewer that an 1000 documents, go trough them by hand. Number of topics depends on the corpora. There is no clear criteria of topics. (Don't you determine the level of abstraction by selecting the ammount of topics over a corpora?) LDA is often used. 

Parsing. You could look at actions or whatever. As long as there are enough of them. It treats a text like a bowl of snippets though. You can treat an image as a bowl of snippets too. You can go into other domains too.

There is a paper on topic modelling. Sub-topic modelling. When Darwin released the origin of species people though more about evolution and the struggle for survivial. Is this true? Its a really difficult thing to anwser. They found that things like strugge for live became more prevalent. Are they related though, is Darwins book a result from something else, or did it originate there. 

### Controlling topic modelling

Sub-topic modelling. Im going to look at Darwin's text to get my topics, and look at a larger corpus then. The next would be to do it by hand, manual vocabulary. You can also filter the meaningfull ones out.

Its a very interesting approach. You need to be carefull though.

-- How effective is topic modelling versus humans?
-- Determine the level of abstraction by selecting ammount of topics? 




 