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


explantion: the command grep searches through multiple files(CH4.txt ch2.txt ch7.txt) for parapgrahs containing the string night in and outputs it. 
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






```
