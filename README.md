# Natural Language Processing LSTM Basic Generation Results Using Symbolic Tokens

## Names Generation(based on [Stepik Samsung AI NLP course](https://github.com/Samsung-IT-Academy/stepik-dl-nlp))
### Examples:

|  |  |  |  |  |
| :---         |     :---:      |          ---: |          ---: |        ---:   |
| Martyushkin| Halushkin| Baidanov| Baidanoff| Zimatov|
| Vakachev| Zhituhin| Velikov| Abdulazyan| Makhorev|
| Jablonov| Atamahov| Dubin| Mashkov| Bakalov|
| Tovashenko| Rozhankin| Andrusichev| Lapinsky| Valennikov|
| Mokhin| Voloseev| Beloishtein| Zhitin| Belovarov|
| Babuhov| Zherkov| Guzin| Zinov| Martyshev|
| Glushin| Tsaramovsky| Batsevich| Shainer| Abdulladzhanoff|
| Babakov| Babashov| Awaloff| Litin| Babakhin|
| Abitov| Turkovich| Grashin| Anorin| Bakhtin|
| Maksyukin| Haleikov| Ponitsky| Gulin| Andrukhin|
| Lihomenko| Antoshkin| Ryzhenko| Shadrahmanoff| Valtsev|
| Badurin| Poltushkin| Awduroff| Gudin| Jarikhin|
| Andrusikov| Rahmanov| Abdugoff| Gulia| Dizhanov|
| Babarov| Turkov| Abdrazyzhin| Pavlushkin| Babashev|
| Patsev| Rahmanov| Averkovich| Zhidin| Muzykin|
| Awdulichin| Rakhmanovich| Guzikov| Babashev| Antoshin|
| Marykov| Rahmanov| Peserev| Zhivailin| Maksievsky|
| Bakhtin| Elenko| Minzhenko| Averkov| Badyanoff|
| Valkov| Tuma| Tumin| Baban| Belomoshev|
| Rakhmat| Prigalin| Makholin| Vaisin| Tikhonushin |

#
## Quotes generation(also based on [Stepik Samsung AI NLP course](https://github.com/Samsung-IT-Academy/stepik-dl-nlp))

Examples: Here we can see that quotes generation using LSTM and symbolic models showing relatively good results. Primarily, we see that model have not learned semantic analysis. I should note that it is more appropriate to use symbolic model on languages that have intensive word generation(not English)
               
#    
>The early ones were something else is the post of the prool of the end.  

>I'm a problem in an all the small from a blessing stuff, and I'll love the man who has an alled that because they do not expect the people are country in the mind of lives that are truth in the time to think that I want to have to talk the same things and some single process.  

>I have never really a sense that are a real and eventield that the ones that they get a book and the one should play the properity. The state is not going to be a big serve world and more to different words.  

>We have like human  was an end, but even traveling steps and in a company some priver and president can trust the souther wrong and our own people when they should be a good company that we create the characters, and the way they are like the same time, don't live a lot of the steps of the sense of divine and hit the same than here was burned the whole eyes to know the universe story elections.  

>The dead is the believer on the actors and women, but the truth and particular ways of student, and the most faith of the most service of the court them to think that life on the mind that has backed to the student than the soul that great security.  

>I used to think the public children.  

>We were all as a dad that people like how to go to the man.  

>I have always been won from other people.  

>I don't think you mean the problem of character.  

>I think about my narder, I think I had some experience of his promised surprising in a world of doing it more. 
#
 ### Examples with same start:
>Humanity is the post the enemy that you feel personally stream of the world of many of the fire of respection to make a school to the leaves and defend the education, and the people who seem to make the sound of having measured and person in a black to have the same things that we have to be involved with the newspation of selling someone who say them about anything that it can feel the characters of writing.  

>Humanity is the actual belief.  

>Humanity is that some universe is to possible to put the world and that doesn't have to do it that a lot of people.  

>Humanity is a big destiny in the estimation of the soul has given the world.  

>Humanity is a superstity of live in the best of course.  

>Humanity is the sense of things about the same people will be a company they are my destruction was the religion of the public states and the sound of determination.  

>Humanity is in the standards that we have no course of dediving their streets in the world that the fact to think that's life for the fact that people come from my house.  

>Humanity is have got them offer a sex productions but the only people so the people are still and start to the future and remown to the traveling and an existence of the heart.  

>Humanity is never been something to respect what they say that all the first books.  

>Humanity is not all the world water and should be an artist.
#
>This scene is not a good thing than a hus of the most players and property to people who should never think you have to accept the sound of the news passion more.  

>This scene is the possible bigger develop in a mother of the capazity of the possible things of people like.  

>This scene is not the respect of joy.  

>This scene is to be found to be an expectated work, but makes a product of progress independent.  

>This scene is the same next people think about the any of the most expectation that they are they are succender.  

>This scene is our things are a cartoon of the ampencipe.  

>This scene is not successful of the power in the world in a very class and when the discussion.  

>This scene is the universe and developing in the fact that I have some movies to do with the most law - sometimes I could do it with the end of the feedered against successful human people who are not looking about the fellow show which was a show.  

>This scene is not very sentimental to get consists the acts of all the people are the world and interest in the same time in the most actor.  

>This scene is a change of life and we understand the years of single movies are not trying to look for being an actor in the cut of the people.
#
## Text Generation With Symbolic Model Using LSTM trained on Dostoevsky Idiot

### Model were trained by cropped sentences just for research interest, because LSTM symbolic model can not remember really long sequences
#
### Some examples:
#
>А я думал, что уж сказал… Я одно такое письмецо получил, для передучить меня маленькую и тоскую  

>Он поворотил назад и прямо по дороге, по которой проходил вчера с Евлечением смотря  

>Вы не отвечаете мне?  

>Не стоите вы все ничего.  

>Если он сейчас не подойдет ко мне, не возьмет меня и не бросит тебя, то бери же его  

>Ну, вот, вздор какой!  

>В последние десять или двадцать минут он говорил, разгорячившись, громко, нетерпеливою  

>Настасья Филипповна проходила в эту минуту мимо самых стульев барышень.  

>Не могу же я получать эти письма!  

>В этом лице… страдания много… – проговорил князь, как бы невольно, как бы сам с собою

>Но разъяснив вам, что меня не так-то легко прожить в положение делать.  

>Право, всё это как-то нелепо и не может быть.  

>Не было бы этого, я, может быть, никогда ему не усказала до считать, – вот к делу,  

>Ну, уж теперь совсем довольно!  

>Тут один Тоцкий.  

>Приличие и чинность чрезвычайные, несмотря на некоторый общий вид семейственности и  

>Князь пригласил его садиться.  

>Почему она один вдруг встал с себя от удивленный вчерашней верлости, развернуть  

>Лизавета Прокофьевна прямо направилась в сторону, противоположную той, в которую направлялись  

>Если бы вы пожили больше с людьми, а в свете, я надеюсь, вам будут рады, как замечательному
#