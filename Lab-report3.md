# Lab Report 3
> the function grep is most commonly used to find strings in a file but there are several ways to implement it

## option 1: grep (string) (filename)
```
example 1:

 input: 
 67$ grep night CH4.txt

output:

In extreme circumstances, when the organization and predictability of the real world fall apart, young children whose prior lives have been ﬁlled with parental warmth and involvement often call on rules and rituals in make-believe to restore their social world. Recently, I came across the recollections of Alice Cahana, an elderly Holocaust survivor, recounting her days as a child in the death camp at Auschwitz. Alice explained that she and her sister Edith managed despite all odds to stay together. Their secret strategy was never to display any emotion that would give away their relationship, since a major objective of the SS was to break up families. Only at night did they dare to hug, whisper, and play together.
On Friday nights, they marked the Sabbath in a special way, by imagining that they were at home. They talked about the evening’s events in minute detail to make the image of family life ﬁrm and real. Alice had always had the responsibility of setting the table, and her mother would correct her if she left out even small, nonessential items. In play, Edith would murmur, “Alice, it’s time to set the table. Find the nicest tablecloths, and don’t forget the ﬂowers. Where are the napkins for the guests? You forgot the fork for Father. You really shined the candelabra beautifully this week, better than before.” 16 After their pretend meal, the two sisters would whisper songs.

After kissing their preschooler goodnight and turning out the lights, many parents are accustomed to hearing refrains like this: “Mommy, Daddy, monsters are in my room again!” To rid the bedroom of scary creatures, pictures and mobiles may have to be removed and a thorough search conducted to assure the child that no monsters are lurking in the shadows, waiting to reappear as soon as the parent leaves. Uncertainty about the relation between appearance and reality also surfaces in other situations. On Halloween, a 3-year-old who eagerly dons her costume may become frightened at the sight of her animal- or witch-like appearance in the mirror. And a father who shaves off his beard and mustache may ﬁnd that his young preschooler reacts with puzzlement and distress to his changed appearance.
That joint make-believe with adults is such great fun is undoubtedly a major reason that 1- to 3-year-olds are so attracted to it. But why is play with adults, at least initially, more engaging than play with peers? While children’s play skills are still limited, adult scaffolding makes play more interesting, surprising, and absorbing. In several studies, 1- to 3-year-olds engaged in more than twice as much make-believe when their mothers were involved than when they were not. In addition, caregiver support led early make-believe to move toward a more advanced level.67 For example, when mothers actively took part, children produced more complex pretend sequences��not just putting the doll to sleep but brushing her teeth, tucking her into bed, singing a lullaby, and kissing her good night. Furthermore, during parent–child play, make-believe themes are more varied, and parents’ verbal commentary is especially effective in raising both the duration and the complexity of play.



explantion: the command grep searches for all parapgrahs containing the string night in CH4.txt and outputs it.

example 2:
input:
68$ grep night CH4.txt ch2.txt ch7.txt 

output:
CH4.txt:In extreme circumstances, when the organization and predictability of the real world fall apart, young children whose prior lives have been ﬁlled with parental warmth and involvement often call on rules and rituals in make-believe to restore their social world. Recently, I came across the recollections of Alice Cahana, an elderly Holocaust survivor, recounting her days as a child in the death camp at Auschwitz. Alice explained that she and her sister Edith managed despite all odds to stay together. Their secret strategy was never to display any emotion that would give away their relationship, since a major objective of the SS was to break up families. Only at night did they dare to hug, whisper, and play together.
CH4.txt:On Friday nights, they marked the Sabbath in a special way, by imagining that they were at home. They talked about the evening’s events in minute detail to make the image of family life ﬁrm and real. Alice had always had the responsibility of setting the table, and her mother would correct her if she left out even small, nonessential items. In play, Edith would murmur, “Alice, it’s time to set the table. Find the nicest tablecloths, and don’t forget the ﬂowers. Where are the napkins for the guests? You forgot the fork for Father. You really shined the candelabra beautifully this week, better than before.” 16 After their pretend meal, the two sisters would whisper songs.
CH4.txt:After kissing their preschooler goodnight and turning out the lights, many parents are accustomed to hearing refrains like this: “Mommy, Daddy, monsters are in my room again!” To rid the bedroom of scary creatures, pictures and mobiles may have to be removed and a thorough search conducted to assure the child that no monsters are lurking in the shadows, waiting to reappear as soon as the parent leaves. Uncertainty about the relation between appearance and reality also surfaces in other situations. On Halloween, a 3-year-old who eagerly dons her costume may become frightened at the sight of her animal- or witch-like appearance in the mirror. And a father who shaves off his beard and mustache may ﬁnd that his young preschooler reacts with puzzlement and distress to his changed appearance.
CH4.txt:That joint make-believe with adults is such great fun is undoubtedly a major reason that 1- to 3-year-olds are so attracted to it. But why is play with adults, at least initially, more engaging than play with peers? While children’s play skills are still limited, adult scaffolding makes play more interesting, surprising, and absorbing. In several studies, 1- to 3-year-olds engaged in more than twice as much make-believe when their mothers were involved than when they were not. In addition, caregiver support led early make-believe to move toward a more advanced level.67 For example, when mothers actively took part, children produced more complex pretend sequences��not just putting the doll to sleep but brushing her teeth, tucking her into bed, singing a lullaby, and kissing her good night. Furthermore, during parent–child play, make-believe themes are more varied, and parents’ verbal commentary is especially effective in raising both the duration and the complexity of play.
ch2.txt:Systematic research reveals both cultural similarities and dierences in adult–child narratives. In an intensive observational study of daily storytelling in two communities—six middle-class Chinese families in Taipei, Taiwan, and six middle-class American families in an Irish-Catholic neighborhood in Chicago—Peggy Miller and her colleagues72 found that preschoolers and their family members routinely narrated past experiences. Most often, they created joint accounts of pleasurable holidays and family excursions—birthday parties, the fair, the zoo, and McDonald’s for the American children; the night market, the zoo, and riding on trains and horses for the Chinese children. Both groups also talked about times the children were ill, sad, or frightened.
ch2.txt:“When our parents split up, we moved with our mom from Arkansas to Seattle. Mom worked all week, weekends, and most evenings. She had to get a career going so there’d be money to live on and to send us to college. Sarah hung out with another family in the neighborhood. A couple of times a week, she had dinner and went to church with them. Looking back, I’d say they were her substitute family; she ‘adopted’ them, and they ‘adopted’ her. I was too young to go o on my own that way. When I didn’t have after-school activities, Mom insisted that I come home and do chores and homework. Sometimes I got to go to a friend’s house to play, but many nights I’d open a can of spaghetti and have dinner by myself. I spent hours daydreaming and looking at old pictures of Mom, Dad, 
Sarah, and me.”
ch7.txt:Children display wide individual differences in the quality of their sibling ties. Once again, temperament makes a difference. For example, arguments between siblings increase when one child is emotionally intense and highly active.39 But parents can do much to foster favorable sibling interaction. During the preschool years, mothers tend to be more positive and playful with second-borns than ﬁrst-borns, and they discipline the older child more.40 This differential treatment is understandable, in that older children are more competent and capable, so parents expect more. But being older also means more privileges—for example, being able to stay overnight at a friend’s house or enroll in certain after-school activities and lessons. These advantages may help compensate for an older child’s perception that a younger sibling is receiving better treatment.


explantion: the command grep searches through multiple files(CH4.txt ch2.txt ch7.txt) for 
parapgrahs containing the 
string night in and outputs it. 
It is usefull for searching multiple files that contain the string
```

## option 2: grep -l (string) *

```
example 1

input:
69$ grep -l night *

output:
CH4.txt
ch2.txt
ch7.txt

example 2
input:
76$ grep -l rice *
output:
chB.txt

explanation: it searches through all the files in the directory for the string rice and outputs the file containing it.
it is useful for locating the files containing the string
```
## option 3: grep -c (string) *

```
example 1:
input:
78$ grep -c night *

output:

chA.txt:2
chB.txt:6
chC.txt:0
chL.txt:4
chM.txt:5
chN.txt:1
chO.txt:0
chP.txt:2
chQ.txt:0
chR.txt:3
chV.txt:0
chW.txt:0
chY.txt:0
chZ.txt:1

example 2:

input:
$ grep -c mice  *

output:
chA.txt:0
chB.txt:0
chC.txt:0
chL.txt:0
chM.txt:0
chN.txt:0
chO.txt:0
chP.txt:0
chQ.txt:0
chR.txt:0
chV.txt:0
chW.txt:0
chY.txt:0
chZ.txt:0


explantion: it searches through all the files in the directory for the string.
if it finds it, the count value of the text file is incremented.
then it returns the count values of all the files, and the number represents the number of times the string appears in the file
this function is super useful for determing number of times a string appears in a directory and in each file specifically. 

```

## option 4: grep -r (string) *

```
example 1:

input:
89$ grep -r mansion *
output:

Rybczynski/ch3.txt:Stylistic consistency is much admired today, but it was not always so. In 1419, Filippo Brunelleschi began the Foundling Hospital in Florence, whose delicate arcade of Corinthian columns surmounted by pedimented windows is generally considered the first building of the Renaissance. At the very same time, he was building a great dome over the crossing of the cathedral of Florence in a style that was not Classical but distinctly Gothic, pointed arches and all. The German architect Karl Friedrich Schinkel is best known for his severe Classical public buildings such as the superb Altes Museum in Berlin, but he also worked in other styles: Gothic in churches, and picturesque Italianate in villas. McKim, Mead & White favored the Classical style for public buildings and palatial residences, but built Norman parish churches, Shingle Style summer retreats, French Renaissance mansions, and American Colonial country houses. John Russell Pope, an eclectic master, designed beautiful picturesque Tudor, Georgian, and Colonial country estates. Edwin Lutyens was another Classicist whose residential work was eclectic.
Rybczynski/ch3.txt:Hunt was 43 when he came into his own. He had established an architectural practice in New York in 1855, almost immediately on his return from the Ecole des Beaux-Arts. He was moderately successful, achieving local renown for the Tribune Building, an early New York skyscraper. Despite his Parisian background, Hunt worked in the prevalent Ruskinian Gothic style. Of his Presbyterian Hospital in downtown Manhattan, the architectural critic Montgomery Schuyler wrote: “The building is of Gothic design with very red brick, and very irregular stone dressings, which, it must be confessed regretfully, are not pleasing to the eye.”3 For his next project, the Lenox Library, Hunt tried something different. He borrowed from the French Neo-Grec style, popularized by Labrouste in the Bibliothèque Sainte Geneviève, adding Renaissance details and his own characteristically vigorous surface modeling. The result was a startling departure from convention, a monochrome limestone block of imposing dignity. The Lenox Library (which 
stood on Fifth Avenue on the site of the present-day Frick Collection) marked a shift in architectural taste, away from Ruskin to a grand and frankly aesthetic Classicism. The 1880s was a decade of great prosperity, and newly wealthy New Yorkers eagerly sought 
out Hunt’s architectural blend of good taste and ostentatious display. He obliged them in a string of high-profile commissions: magnificent mansions along Fifth Avenue, country houses on Long Island, and palatial “cottages” in Newport, Rhode Island. Hunt died in 1895, but in the last seven years of his life, he completed more than fifty projects.




example 2:
input:
94$ grep -r colony *
output:
Castro/chP.txt:Their primary religious ceremonies commemorated the passion and death of Jesus Christ, during the celebrations of Semana Santa, “Holy Week.” It is speculated that the starting date of the brotherhood is somewhere between 1790 and 1810. The origins of Los Penitentes have been debated for years, but it is likely they were heavily influenced by the Franciscan Third Order, who were the friars in New Mexico until Mexico separated from Spain in 1821. Los Penitentes became a strong institution in rural New Mexico because there were too few Catholic priests to oversee the religious life of the people during the early nineteenth century. The village chapters governed themselves without benefit of the few priests in the colony. Consequently Los Penitentes had strong influences in conserving the language and culture of the Spanish Americans of New Mexico. Membership consisted of between thirty and fifty adult men per chapter (called moradas) and were divided into two groups: common members, called hermanos disciplantes (brothers who discipline), and officers, called hermanos de luz (brothers of light). By the early twentieth century the various chapters had become secret societies with restricted membership.
Castro/chR.txt:Eventually every Chicano community had its own parish, due usually to the commitment and work of one individual priest in the diocese. There is probably a Virgen de Guadalupe parish in every single Mexican community in the United States. In spite of the fact that in some regions there was hostility by church officials, the importance of the Catholic Church in creating Chicano communities cannot be overemphasized. It was the church that created an environment where people could speak Spanish; celebrate 
religious, social, and political ceremonies; cook the special foods of the holy days and holidays; and of course pray together. The experience of Chicanos in Kansas, as described by Beeson, Adams, and King, was repeated throughout the Southwest and Midwest. “The church remained the most powerful center and cohesive force in the Mexican American colony. It was a religious and social haven in an alien, often hostile, environment. In the church the immigrant could use his Spanish language, wear traditional costume, celebrate Mexican Independence Day with a fiesta, and eat traditional food. The church also perpetuated the separateness of the Mexican Americans and their Anglo neighbors” (Beeson, Adams, and King, xx).
Fletcher/ch2.txt:What, then, is the point of the Declaration’s claim that all men are created equal? The answer is twofold. First, there is an implicit claim that as a people the Americans are equal to the British and to all other peoples. If any people should 
be able to consent to their government, then the Americans, too, enjoyed that fundamental right. That they were a colony—nurtured as the metaphoric child of the Crown—did not mean that they could not assume the posture of an equal people. If this is the meaning of equality in the Declaration, then it provides little support for Lincoln’s claim that the nation was dedicated to a proposition that implicitly required the abolition of slavery.
Kauffman/ch4.txt:Bluntly in front of us: The closure of catalytic and work tasks in an autonomous agent by which it genuinely constructs a rough second copy from small building blocks by adroit linking of exergonic and endergonic processes. A cell, or colony of cells, is propagating this organization of process.
Kauffman/ch4.txt:Autonomous agents achieve catalytic and propagating work-task closures by which they build copies of themselves. The myriad sensors, receptors, ligands, enzymes, and linked reactions of metabolism are the structure and dynamic of the reproducing cellular autonomous agent that constitutes the measurement, detection, recording, and search for useful energy sources to link into its ongoing construction of itself. The propagating closure of events and organization that is a cell or colony of cells, an autonomous agent, or a collection of autonomous agents is not matter alone, energy alone, entropy alone, nor the negation of entropy, Shannon’s information, alone. The propagating closure that is an autonomous agent appears to be a new physical concept that we have not known how to see before.
Kauffman/ch5.txt:But back to the past. Dennett distinguishes “Darwinian creatures,” “Pavlovian creatures,” “Popperian creatures,” and “Gregorian creatures.” A simple autonomous agent, say, a bacterium, is a Darwinian creature. In its simplest version, the creature evolves by mutation, also recombination and natural selection. For the moment, no behavioral learning is to be considered. So one (or a colony or an ecosystem) of Darwinian creatures adapts more or less as Darwin told us.
Kauffman/ch9.txt:Go for lunch, and dinner, and come back the next day. In general, among the , coplated pairs of bacteria, while all , colonies will have grown, a single pair will have grown to the largest mixed red-blue bacterial colony. Say the largest mixed 
red-blue colony corresponds to red secreting molecules per second, blue secreting molecules per second.
Kauffman/ch9.txt:This gedankenexperiment is important, for the exchange ratio of red and blue molecules is the analogue of price, the ratio of trading of oranges for apples. And there exists a ratio, red molecules to blue molecules per second, that maximizes the growth of the mixed red-blue bacterial colony. Since the fastest growing mixed red-blue colony will exponentially outgrow all others and dominate our gedankenexperiment petri plate, this red-blue pair establishes “price” in the system at red to blue molecules. Further, in the fastest growing red-blue colony, where red secretes molecules and blue secretes molecules per second, both the red and blue bacteria in that mixed colony are replicating at the identical optimum rate. As discussed in chapter , using a rough mapping of biology to economics, that rate of replication of a bacterium corresponds to economic utility and the increased the rate of replication corresponds to increased economic utility. The red and blue bacteria not only establish price, but they also share equally the advantages of trade present along the Pareto-ecient contract curve in the Edgeworth box discussed in chapter .




explanation: It searches through all the files in the subdirectories for paragraphs containing the string
then it returns all the parapgrahs containing the string.
The function is useful for searching through all the files in the directory and the subdirectory. so you don't have to change directory
to search through everything. 


```


> sources for my findings above are from 

> https://phoenixnap.com/kb/grep-command-linux-unix-examples


>  and I tested these functions on the written_2 from the git hub directory


> side note: some of the output code got blurred out due to it not all fitting on the same page
