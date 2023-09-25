# 👩🏽‍🔧 Srinjana's Personal Website ![fa057582f44b477206a32e255bb8ca18](https://github.com/srinji5141/srinji5141.github.io/assets/105142919/961bb890-d0f9-40aa-8044-752e6160f01f)

![img](https://github.com/srinji5141/srinji5141.github.io/assets/105142919/0d23e390-e01b-4c21-8673-13bb53b63911)

Hi there 👋🏽 My name is Srinjana Sriram and I'm an undergraduate Math/CS student, at UCLA. I'm passionate about problem-solving, amongst other things. Over here, you'll be able to find more information about some of my past projects and other interests. Feel free to explore and find out a little bit more about _who I am_ and _what I like to do_.

## Menu

- [Projects](#projects-)
- [Papers and Publications](#papers-and-publications-)
- [Pitch Decks and Presentations](#pitch-decks-and-presentations-)
- [Problem-Solving and other Educational Resources](#problem-solving-and-other-educational-resources-)
- [Hobbies](#hobbies-)
- [Connect with Me](#connect-with-me-)

## Projects 👩🏽‍💻📟

### Project 1: EchoGreet, UCLA MakerSpace

**Description**

While exploring the UCLA MakerSpace, I made a clap-activated LCD greeting panel, using an Arduino Uno, a few jumper wires, resistors, capacitors, a breadboard, a LM358 op-amp, an electret microphone, and a gwt-c1627a-rgb v1.1 liquid crystal display.

**Repository**

```cpp
#include <LiquidCrystal.h> // Includes the LiquidCrystal Library 
LiquidCrystal lcd(3, 2, 4, 5, 6, 7); // Creates an LCD object. Parameters: (rs, enable, d4, d5, d6, d7)
...
```

For the complete code, visit [https://github.com/srinji5141/EchoGreet/blob/main/helloworld.ino](https://github.com/srinji5141/EchoGreet-UCLA-MakerSpace/blob/main/helloworld.ino)

![image](https://github.com/srinji5141/EchoGreet/assets/105142919/0190b8ea-35eb-4f8e-9dc5-22d5fe8e7bc0)

For the complete circuit design, visit [https://github.com/srinji5141/EchoGreet-UCLA-MakerSpace/blob/main/README.md](https://github.com/srinji5141/EchoGreet-UCLA-MakerSpace/blob/main/README.md)

**Demo**
![VIDEO-2023-05-27-16-21-38](https://github.com/srinji5141/srinji5141.github.io/assets/105142919/c73bb2cb-1b19-49f2-aac2-c61579e6172a)

### Project 2: American Bar Association Free Legal Answers User Records EDA, ASA DataFest 2023

**Description**

During the 2023 ASA DataFest, my team and I explored why certain client questions experienced response time lags from laywers, on the American Bar Association's Free Legal Answers virtual advice clinic. To do this, we cleaned our dataset of unrelated, and missing data. We explored variables such as time stamps, and created more meaningful variables such as time durations. We then plotted this data in histograms, pie charts, and scatter plots to understand the geographic spread of this data. We then continued to text mine the client questions and analyse which particular questions were experiencing time lags, which we represented through word clouds

**Skills**: data pre-processing, feature engineering, data analysis, summary statistics, data visualisation, text mining, data manipulation etc.

**Notebook Link**: [https://colab.research.google.com/drive/12J91HZHFGJDgecqVG6SmbZxZhspmF7ZB?usp=sharing](https://colab.research.google.com/drive/12J91HZHFGJDgecqVG6SmbZxZhspmF7ZB?usp=sharing)

**Project Poster**

<img width="438" alt="Screenshot 2023-09-03 at 5 27 05 PM" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/30fc16ab-13e4-4e83-9459-2d0ef4442417">

[Project Poster.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12508361/C10Boo.lean.Busters.pdf)

### Project 3: SentiBot, LAHacks 2023

**Description**

During the 2023 LAHacks, my team and I built a sentiment analysis trading bot, which automatically outputs trading recomendations based on user-specified market and asset classes. It works by webscraping for recently published articles, based on those specifications, and then classifies them, according to their degree of positivity, using Cohere's NLP models.

**Repository**

The following code snippet trains Cohere's NLP classification model to identify whether the webscraped article titles are about company stocks or not.

```python
import cohere
from cohere.responses.classify import Example
...
```

For the complete code snippet, visit [https://github.com/srinji5141/SentiBot-LAHacks-2023/edit/main/SentiBot.py](https://github.com/srinji5141/SentiBot-LAHacks-2023/edit/main/SentiBot.py)

**Demo**

<img width="753" alt="SentiBot" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/9156973a-04cd-42d2-96fc-d81232b83a7f">

To watch a full demonstration of SentiBot, visit [https://devpost.com/software/sentibot-un7qmy](https://devpost.com/software/sentibot-un7qmy)

### Project 4: Professional Contacts Management Program

**Description**

To address a personal challenge of managing professional contacts, I developed a custom LinkedIn Web Scraper. This tool automates dynamic website navigation, and extracts the biodata of over 500 "Connections" within the LinkedIn "My Network" section. It then conveniently organizes the collected information into a .tsv file. This .tsv file acted as an effective resource for me, as it helped me keep track of my professional interactions, such as cold-emailing etc.

**Repository**

```python
from selenium import webdriver
from selenium.webdriver.common.by import By
...
```

For the complete code, visit [https://github.com/srinji5141/Professional-Contacts-Management-Program](https://github.com/srinji5141/Professional-Contacts-Management-Program)

Feel free to run the above code, with your login details, and download all your contacts' details into a .tsv file, for simple professional contacts management!

### Project 5: World Happiness Index Report, UCLA Statistics Club

**Description**

To look into international developmental metrics, my partner and I explored [Kaggle's World Happiness Report Dataset](https://www.kaggle.com/datasets/unsdsn/world-happiness). We first cleaned the dataset, and then created correlation matrices, as well as summary statistcis on metrics such as GDP per capita, life expectancy, social support etc. We also plotted histograms of happiness scores over the years, as well as over continents to understand the spread of data. Finally, we conducted some predictive analytics through linear regressions on happiness scores and GDP per capita.

**Skills**: data pre-processing, data analysis, summary statistics, data visualisation, data manipulation, linear regression, principal component analysis, k-means clustering, etc.

**Notebook Link**: [https://colab.research.google.com/drive/1gTCRITuahCMoxXAWANOLqniY-mNxbIZs?usp=sharing](https://colab.research.google.com/drive/1gTCRITuahCMoxXAWANOLqniY-mNxbIZs?usp=sharing)

### Project 6: MidnightMindfulness.com

**Description**

In order to combat the post covid-19 effect, I built a randomised intention-setting website as a creative project to play around with, when feeling bouts of demotivation or lack of focus.  

**Repository**

```javascript
let intention = [" Take it easy 😎 ", " Be present and connected 🎁 ", 
" Set a goal for today 🦾 ", " Forgive others and yourself 🫀 ", 
...
```

For the complete code, visit [https://github.com/srinji5141/MidnightMindfulness.com](https://github.com/srinji5141/MidnightMindfulness.com)

**Demo**

<img width="1470" alt="MidnightMindfulness" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/0d4ba83d-d774-4c8e-9627-acd1efc14719">

To play around with the website, visit [https://srinji5141.github.io/MidnightMindfulness.com/](https://srinji5141.github.io/MidnightMindfulness.com/)

### Technologies 

<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> </p>

⏪ [Menu](#menu)

## Papers and Publications 👩🏽‍🎓📝

### Cobb Douglas Function: Optimising **student happiness** based on play time and study time

Hoping to model optimization through multivariable calculus, I embarked on a personal journey of answering, how we can achieve work-life balance. Drawing from economics' concept of utility functions, this paper explores mathematical approaches to optimize the satisfaction of students with different study routines. Through data collection and mathematical modeling, I used derivatives, contour lines, and the Lagrange multiplier, to offer insights into managing our personal and professional lives.

**Download Link**: [Cobb_Douglas_Function.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390671/sriram.SRINJANA.Extendedessay.May2021.pdf.-.HL.MAA.SCORED.A.pdf)

**Research Gate Link**: [https://www.researchgate.net/publication/374153474_Cobb_Douglas_Function_Optimising_student_happiness_based_on_play_time_and_study_time](https://www.researchgate.net/publication/374153474_Cobb_Douglas_Function_Optimising_student_happiness_based_on_play_time_and_study_time)

**DOI**: 10.13140/RG.2.2.36022.47688
  
### Queueing Theory: Optimising wait times at **boba stores**

Motivated by my love for boba, I decided to use probability and statistics to enhance the boba store experience. Through using the M/M/1 model from queueing theory, a type of stochastic process, this paper aims to answer the question: can Mathematics expedite wait times at boba stores?

**Download Link**: [Queueing_Theory.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390672/sriram.SRINJANA.MAAHL.IA.Mathexploration.May2021.pdf)

**Research Gate Link:** [https://www.researchgate.net/publication/374153587_Queueing_Theory_Optimising_wait_times_at_boba_stores](https://www.researchgate.net/publication/374153587_Queueing_Theory_Optimising_wait_times_at_boba_stores)

**DOI**: 10.13140/RG.2.2.29311.59042

### Regulation VS Deregulation: What is the optimal level of government intervention, in the Singaporean market?

Inspired by John Komlos' philosophy of humanistic capitalism, my partner and I explored the intricacies of protecting Singapore's competition and consumers. In an age of digitsation and globalisation, this paper uncovers potential threats and proposes a three-pronged solution of monitoring, consultation, and regulation. Through case studies, we underscore the need for diligent oversight within Singapore's unique policy framework, which harmonizes state and market efforts.

**Download Link**: [Regulation_VS_Deregulation.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390688/1692363990902.pdf)

**Research Gate Link**: [https://www.researchgate.net/publication/374153726_Regulation_VS_Deregulation_What_is_the_optimal_level_of_government_intervention_in_the_Singaporean_market](https://www.researchgate.net/publication/374153726_Regulation_VS_Deregulation_What_is_the_optimal_level_of_government_intervention_in_the_Singaporean_market)

**DOI**: 10.13140/RG.2.2.10437.22241

### Mathematics: The foundation of the universe 

Motivated to enhance student engagement with Math, I created this Math-themed colouring booklet to kindle a sense of curiosity about the vast world of Mathematics, amongst young learners.

**Download Link**: [Mathematics.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390719/Mathematics_.The.Foundation.of.the.Universe_Draft_2.pdf)

⏪ [Menu](#menu)

## Pitch Decks and Presentations 👩🏽‍🎤🎤

### Amazon Web Services Innovation Challenge Final Presentation
Won 1st Place

As part of the Data Rangers team, for the AWS Innovation Challenge, I was able to develop a data-driven gamified social media platform for the LA 2028 Olympics. Our solution aimed to address declining viewership by engaging users in daily challenges, real-time trivia, and community leaderboards.

Our pitch deck included a problem statement, a [Figma mockup](https://www.figma.com/proto/Fd5rzxMQhipRqesRBQ11u2/MedalUp?type=design&node-id=1-3348&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A3348) of our application detailing the user journery, as well as a data pipeline explaining how we would attempt to create custom daily challenges. It also featured a market analysis, a business plan, and an implementation timeline.

We had the honor of presenting our application at the LA2028 office and securing incubation at the AWS Cloud Innovation Center.

[AWS-Deck.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390428/Team5-DataRangers-Pitch-Deck.pdf)
<img width="1397" alt="Screenshot 2023-08-20 at 7 35 30 PM" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/44c75d06-01d1-41b3-ba9b-1887714976d1">

### Boston Consulting Group Case Competition Final Presentation
Won 5th Place

As part of BCG's annual case competition at UCLA, my team and I evaluated growth opportunities within the US video game industry. More specifically, we focused on whether Blizzard Entertainment should venture into the US streaming industry through a TV adaptation of their beloved game, Overwatch.

Our presentation included a thorough industry SWOT analysis, a comprehensive examination of Blizzard Entertainment and its competitors, and a case study of Arcane. We were lucky enough to make it to the final round of the case competition, where we presented our findings to a panel of BCG judges.

[BCG_R2-Deck.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390488/Srinjana_Sriram_FR.pdf)
<img width="1396" alt="Screenshot 2023-08-20 at 7 37 19 PM" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/29672b96-69d8-4d97-8830-7b01f0acd572">

[BCG_R1-Deck.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390493/BCGxUconsultingR1.pdf)
<img width="1396" alt="Screenshot 2023-09-01 at 3 35 40 AM" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/0c9f838f-0e1e-4c22-99cc-7a0eb32f031a">

### BruinLabs Product and Business Competition Final Presentation
Won 3rd Place

As part of the BruinLabs summer program, my friends and I collaborated on SWAP: a web application designed for crowdsourced item borrowing. Through the program, we learned the nuances of entreprenuership and product development.

[BL-Deck.pdf](https://github.com/srinji5141/srinji5141.github.io/files/12390497/BruinLabs.Team.8.SWAP.Pitch.Deck.pdf)
<img width="1467" alt="Screenshot 2023-08-20 at 7 41 26 PM" src="https://github.com/srinji5141/srinji5141.github.io/assets/105142919/0ccc1e00-e45f-4321-b4cf-a6a55b8b8877">

⏪ [Menu](#menu)

## Problem-Solving and other Educational Resources 👩🏽‍🚀🔭

### Acing the IBDP (International Baccalaureate Diploma Programme)

A drive filled with A graded internal assesments, extended essays, past papers, notes, and sample college essays, compiled and written by myself, for struggling IBDP students.

**Google Drive Link**: [Srinji's Gift :)](https://drive.google.com/drive/folders/1KKp9rTbwYcvyuR-9E4dTBe4GQKhPts6J?usp=sharing) 

⏪ [Menu](#menu)

## Hobbies 👩🏽‍🎨🖌️

🎨 Growing up, I did a lot of art which I like to post about, from time to time, on my [WordPress](https://srinjana.wordpress.com/author/srinjana/).

<a href="https://ibb.co/qDhk78G"><img src="https://i.ibb.co/qDhk78G/Screenshot-2023-08-20-at-6-29-57-PM.png" alt="Screenshot-2023-08-20-at-6-29-57-PM" border="0"></a> <a href="https://ibb.co/MpjYBcd"><img src="https://i.ibb.co/MpjYBcd/Screenshot-2023-08-20-at-6-29-22-PM.png" alt="Screenshot-2023-08-20-at-6-29-22-PM" border="0"></a> <a href="https://ibb.co/nzP08L3"><img src="https://i.ibb.co/nzP08L3/Screenshot-2023-08-20-at-6-29-31-PM.png" alt="Screenshot-2023-08-20-at-6-29-31-PM" border="0"></a> <a href="https://ibb.co/rmdQqNG"><img src="https://i.ibb.co/rmdQqNG/Screenshot-2023-08-20-at-6-29-44-PM.png" alt="Screenshot-2023-08-20-at-6-29-44-PM" border="0"></a>

💅🏽 Nowadays, I don't have as much time to paint on canvas, so I try to paint my nails instead!

<a href="https://ibb.co/9syDSgz"><img src="https://i.ibb.co/9syDSgz/IMG-6081.jpg" alt="IMG-6081" border="0"></a> <a href="https://ibb.co/y0MbZpt"><img src="https://i.ibb.co/y0MbZpt/IMG-6082.jpg" alt="IMG-6082" border="0"></a> <a href="https://ibb.co/bHFRRwt"><img src="https://i.ibb.co/bHFRRwt/IMG-6083.jpg" alt="IMG-6083" border="0"></a> <a href="https://ibb.co/xhkVC9M"><img src="https://i.ibb.co/xhkVC9M/IMG-6084.jpg" alt="IMG-6084" border="0"></a>

⏪ [Menu](#menu)

## Connect with Me 🤳🏾☎️

Feel free to contact me via [E-mail](srinjana.sriram@gmail.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/srinjana-sriram/).

- **E-mail**: [srinjana.sriram@gmail.com](srinjana.sriram@gmail.com)
- **LinkedIn**: [https://www.linkedin.com/in/srinjana-sriram/](https://www.linkedin.com/in/srinjana-sriram/)
- **GitHub**: [https://github.com/srinji5141](https://github.com/srinji5141)
- **Wordpress**: [https://srinjana.wordpress.com/](https://srinjana.wordpress.com/) 
- **Instagram**: [https://www.instagram.com/srinjana_sriram/](https://www.instagram.com/srinjana_sriram/)

⏪ [Menu](#menu)

Thank you for visiting my personal website. I hope you enjoyed!

![mw4y58i658981](https://github.com/srinji5141/srinji5141.github.io/assets/105142919/08bd7761-5a2a-4aad-ac81-94780c514374)

