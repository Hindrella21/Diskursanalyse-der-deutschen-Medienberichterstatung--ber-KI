# Diskursanalyse der deutschen Medienberichterstatung über KI
Eine Analyse von Schlüsselwörtern und thematischen Strukturrn im deutschen Mediendiskurs über KI
# Diskursanalyse der deutschen Medienberichterstatung über KI
Eine Analyse von Schlüsselwörtern und thematischen Strukturrn im deutschen Mediendiskurs über KI
## I.💻*Background and Objectives*
 How does the German mainstream media construct its discourse against the background of the global hot topic of Artificial Intelligence (KI)? 
 Taking the news about *"Kunstliche Intelligenz"* on Zeit Online as the corpus and Fairclough's three-dimensional model as the basis, 
 this profile explores how the media participates in the shaping of technological discourse in terms of vocabulary usage, 
 thematic distribution, and socio-ideological dimensions.
 
## II. 📖*Research Process and Methodology Steps and Tools*
### 1. 💬Word frequency analysis and word cloud generation
Explore the most frequent entities and Wordcloud generation and keywords in the corpus.
NLTK, WordCloud Counter
### 2. 🎶Collection Analysis
Analyze the co-occurring words around high-frequency words, identify the sliding window of semantic relationships, spacy.
### 3. 🔲Topic Modeling 
To categorize news topic using LDA, mining structural discourse frameworks.
### 4. 🔳Comparative analysis of social practices
Contextual interpretation of policy documents in the context of German AI policy, business dynamics, EU regulation + manual comparison.

## III. ☁️*Stage 1 result: word frequency Wordcloud interpretation*

<img alt="Wordcloud" src="/Users/jym/Desktop/Unknown.png" width="300" height="200"/>

The most frequent keywords in the graph include:
1. ***💁🏻‍♂️Countries and people***: USA, China, Deutschland, Trump, Musk, Donalt
2. ***🛸Business and technology***: Google, Apple, OpenAi, Nvidia Unternehmen
3. ***🏛Social concepts***: Menschen, Inhalt, leben, registrierung, Datenschutz

## Preliminary findings:
 - The focus of the discourse is not purely technical, but highly politicized and social;
 - AI is placed in complex contexts such as US-China competition, multinational corporations, and data control;
 - Words like "müssen", "sollen", "macht" point to a commanding discursive tendency.

## IV. *Stage 2 program: in-depth analysis of pathway collocational word analysis*
***Goal***: Analyze the semantic construction of words, such as KI, Menschen, Macht, China, etc.
1. Center words collocated with high-frequency words(5 words)  

[('nicht', 22), ('von', 20), ('für', 18), ('mit'. 17), ('Zu', 16), ('wie', 14), ('auch', 11), ('es', 11), 
('oder', 10), ('kann', 9), (' wird', 9), ('als', 8), ('um', 8), ('bei', 8), ('an', 7), ('auf', 7), ('Bereich', 7), 
('aber', 6), ('Der', 6), ('noch', 6), ('nach ', 6), ('-, 6), ('im', 6), ('Unternehmen', 6), ('man', 6), ('vor', 5), 
('durch', 5), ('soll', 5), ('dem' , 5), ('wenn', 5), ('Sie', 5), ('andere', 5)].

2. Important high-frequency real words: observing the "conceptual field"
*Example meanings and tendencies of real word categories*
 - 📦Field words  
 **Bereich Unternehmen Entwicklung Prozesse, Geräte**
 AlI is embedded in specific technological/industrial contexts, emphasizing its practical application.
 - 🌏Geopolitics  
 **USA Europa Meta**
 Involves states and corporations, suggesting issues of technological dominance and platform monopolization! Risk and Ethics.
 - ☄️Risk and Ethics  
 **nicht keine warnt dabei ohne Übernehmenn**
 Reflects the media's concern that AI could get out of control.

3. Verb vocabulary suggests media discourse tendencies
 **kann wird macht nutzt entwickeln 1ässt** ➡️ Enabling, progressive language
 **warnt, Übernehmen, ohne kontrollieren** ➡️ a risk warning discourse
 **so11 muss dürfen** ➡️ directive, disciplinary discourse
 🪡***Conclusion***: The media context around "K" shows a mixture of "techno-optimistic" and "control-anxious" discourses at the same time.
 
### Conclusion： Combining the textual dimension of critical discourse analysis with the textual dimension of critical discourse analysis
 **CDA analysis dimensions found**  
 *Lexical choices*  
 AI is described as a capable, functional, and broadly phenomenal grammatical position.  
 *Syntactic position*  
 Most sentences appear in analytic, explanatory constructions (e.g., "KI kann.", "Mit Kl wird...")  
 *Discourse features*  
 Both empowering discourse and risky discourse (warning/ethical concerns)  
 *Subject use*  
 "Menschen", "Unternehmen", "wir", "Meta", "Europa" ➡️ public, private, geopolitical power structure involved  

## VI. 🧠*LDA Theme Analysis and Interpretation (7 themes in total)
### 🟥Theme 1: Everyday Socialization and Human-Computer Interaction
 **Keywords**: ki, zeit, menschen, online, chatgpt, schon, immer, sei, mehr, openai
 *Interpretation*:
 - Emphasizes the connection of K1 to everyday life, human communication, and online contexts;
 - The presence of chatgpt openai suggests the topic of novel generative AI;
 - Words such as “zeit”，“menschen”，“schon” reflect the gradual integration of AI into the public consciousness.   
**Corresponding discourse types**:  
humanistic discourse, popularization discourse, anthropomorphic interaction perspective   

### 🟧Theme 2: U.S. Political Figures and Policy Discourse
 **Keywords**: us, trump, usa, donald, zeit, zolle, prasident, regierung, sagte, wurde
 *Interpretation*:
 - Focuses on the use of AI topics in the context of the Trump era and the US-China trade war;
 - “zölle”, "Regierung"... suggests a geopolitical discourse domain.      
**Corresponding discourse types**:    
national leader discourse, power control discourse, media citation discourse   

### 🟨Theme 3: China-US Game and Future Expectations
 **Keywords**: china, mehr, usa, 000, us, deutschland, 2025, menschen, sagt, zeit
 *Interpretation*:
 - china usa, deutschland 2025 is clearly a discourse of "future dominance of AI";
 - The presence of the quantifiers eea year, transnational countries suggests a possible strategic or economic forecasting text.   
**Corresponding discourse types**:    
developmentalist discourse, international competition discourse.   

### 🟩Theme 4: Politics, Military and AI Ethics
 **Keywords**: mehr, zeit, spd, zudem, union, ukraine, menschen, prozent, us, drohnen
 *Interpretation*:
 - Emergence of spd, union, ukraine drohnen, etc. one relates to the position of political parties with AI military applications;
 - menschen prozent denotes related to public opinion, influence analysis.      
**Corresponding discourse types**:    
political-ethical discourse, war discourse, public influence discourse   

### 🟦Theme 5: EU Regulatory and Product Issues
 **Keywords**: inhalt, abopfiichtiger, eu, deutschland, pro, zeit, oppo, xiaomi, gibt, s25   
 *Interpretation*:    
 - eu abopflichtiger, deutschland inhalt-alludes to content regulation and subscription content issues at the EU level;
 - opp9 xiaomi,s25 appears as cell phone model one potentially AI and end product related topics.     
 **Corresponding discourse types**:   
regulation/subscription discourse, consumer technology discourse     

### 🟪Theme 6: AI giant corporate economic discourse
 **Keywords**: ki, uS,apple, unternehmen, google, do11ar,nvidia, intelligenz, mehr, milliarden
 *Interpretation*:
 - Typical Platform Capital Discourse I Corporate, Money, Technology Focus;
 - apple google nvidia milliarden dollar Explicitly points to the capitalization of the AI industry.     
 **Corresponding discourse types**:    
technology corporate discourse, market-driven discourse    

### ⬛️Theme 7: Musk and his technological hegemony discourse
 **Keywords**: musk, ki, inte11igenz, openai, nilliarden, dollar, elon, kinstliche, xai, monster
 *Interpretation*:
 - Emergence musk elon xai, monster- intensely personalized technological discourse (Musk myth);
 - monster, kinstliche intelligenz May contain negative metaphors with sci-fi rendering.     
 **Corresponding discourse types**:      
heroicization discourse, risk discourse, spectacle discourse
