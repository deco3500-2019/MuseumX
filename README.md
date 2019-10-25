# Team MuseumX
Read our [Proposal](https://github.com/zhijiang95/MuseumX/wiki/Proposal) over at our Wiki!
Chuike Lee
Elena Panova
Emma Safarova
Zhijiang Wang

# Inside Art
![Zhijiang_final-01](https://user-images.githubusercontent.com/54301507/67284828-b3245100-f519-11e9-84e2-40e98d0f1258.png)
# Prototype 
####
  -Link to the Figma prototype (Emma)
  
  -Link to the Picture Prototype (Chuike)
  
  -Link to the Arduino Prototype (Lena)
  
  -Instructions for how to deploy and use it, any login credentials; (Emma, Chuike, Lena)
  For picture in Prototype:
  - downloand and open SOMO project 3 in Visual Studio Code (the blue one)
  - open index.html to see keywords listed at the top of the page
  - add photo to the images folder in SOMO project 3
  - save photo name as keyword (ending file name with .png) corresponding to keyword chosen by participant
  - refresh index.html in browser window
  - 'select' or 'click' the keyword button at the top of the page
  - the participant's image will go to keyword position on the artwork
  - find participant's image
  - click on participants image to reveal a description specific to the keyword only
  - close that description click 'x'
  - to form a new connection, save image as a new keyword (ending filename with .png)
  - click on the corresponding keyword button on index.html
  - find participant's image and click on it to reveal description specific to that keywork only
  - there are 8 keywords in this prototype (the process can be repeated 8 times)
  
# Project Overview
#### Problem space (Emma)
  
#### Design process
    how did you tackle this problem? Use images and extended captions to
    explain the design process and how your ideas evolved. Mention any limitations and
    relevant theory.
         
##### Process diagram (Zhijiang)
![diagram-01](https://user-images.githubusercontent.com/54301507/67487873-121cce00-f6b2-11e9-8a45-0e3cbe88fff5.png)
##### How Ideas Evolved (Zhijiang)
We generate several ideas based on the insights we gained from literature review and contextual enquiry.

###### stage1
The original concept is named “about the artist(token projection)”, This is a pocket-sized tangible projection that will be given (optional/ if they want it) to visitors upon entering the gallery. There are sockets allocated to each artwork and the gadget is pluggable to them. When the visitor plugs their gadget into the socket, then the token will  project background information about and digital version of this artwork.

###### Stage2 
Then our group reviewing this concept from several aspects. Although the projection feature enable user to see more details about the artwork and description, there are limitations about this concept. first is the technique issue, it is hard to integrate the projection with token, which require massive works and it is not necessary for users to carry this device , if there is no unique experience.

###### Stage3 
Then we put our sights back to the literature review, the study of shared mobile display for this space (Lanir, Wecker, Kuflik, & Felberbaum, 2016) does indicate that a shared larger display does motivate group cohesion, should everyone participate in a collective tour of the exhibition. And the previous research from also indicated that visitors evoked "rich sensory relationships to some of the tangible objects" and that people valued them as a physical reminder of their interaction in a museum. Based on these insights we develop our concept to be a digital screen which allow user to zoom in and zoom out. Also for making this experience more unique, we added “face into the painting features”. 

###### Stage4 
Due to this is a quite special feature, we are not sure the user’s acceptance. We conducted a workshop to test user’s acceptance and motivations. The participants are asked to provide their personal hobby and favourite colour. Then we provide the similar theme painting for them. Regarding the feedbacks, we found that most participants did not form connections based on the description provided. The information in the description may not have been specifically connected to the keywords provided for the participants in the workshop. So we decided to find keywords from artwork first by digging deep story of the painting, then provide users keywords. 

##### Workshop Design
After the final concept was established and discussed, the team decided to organize a design workshop. The team decided to use this design method in the research as it was considered as a most useful step at this stage of the project which will allow not only to evaluate our idea but also help to invite users to the co-design process. The co-design process was most appropriate at this stage: instead of providing users with possible solutions, it was interesting to get inspirations from users and don’t limit them with the existing ideas. 

Therefore the workshop purpose was to understand:
- how the digital version of the artwork and ability to explore it digitally (f.e zooming-in/out) 
- changes users’ emotions/attitude towards the art;
- how to build a personalization process: questionnaire/ keywords/ other;
- how to integrate a person in the piece of art;
- how users perceive the concept, and which things to improve for a better connection of visitor to the artwork.

As a preparation step for the workshop participants were asked to provide their photos and fill in the questionnaire and after answers were collected, pictures that have some connections with the them and relevant descriptions were prepared for each participant.

Design Workshop Protocol: https://docs.google.com/document/d/1dTj3EC6-76zk9LSGiw27iAMTPqj1vOeoQIDVdMwZf0A/edit


##### Workshop process & results (Chuike)
##### Final Prototype Deign 
The goal of the prototype was to provide an opportunity for visitors to evaluate our concept and to understand if the goal of our project in promoting connection will be achieved. To achieve this, team MuseumX decided to imitate the end-to-end scenario starting from the gathering personal data (keywords and photos), their interaction with a tangible device that will guide them through the exhibition, and lastly the experience with a digital version of painting where visitors could see themselves inside the art objects. The idea was to imitate the context by providing an environment that will be close to reality. Therefore artworks were also printed and placed on the walls. To achieve the personalization aspect and later evaluate the connection between participants, the prototype included interaction with the digital screen that will be their first step when they will come to the exhibition. The prototype was created in Figma and comprised of serious steps that guided participants through the initial stages. The interface contained the stage when participants were asked to choose keywords that were initially derived from pictures with pre-established text descriptions related to them. After this stage participant was provided with a digital token (done using Arduino) that vibrated when he/she reached picture connected to him. This stage was imitated through manually triggered vibrations as all keywords led to the same artwork. This was done due to the limited time that the team had between taking a photo and showing a digital picture. Then visitors were provided with digital version of the painting with their photo incorporated in the artwork (done by HTML/CSS/JavaScript). Participants were asked to find the connection and then to read a description related to this specific scene. Each description was prepared in a way to be related to the context of the chosen keyword. 

##### Results & future improvements (Chuike)
    
#### Task allocation (Each)
Lena Panova: 
  - Analysis of 2nd round interviews
  - Initial protocol of the Design Worshop
  - Tangible devise (Arduino)
  
  Chuike Lee
  - Analyse workshop findings
  - Implications for design
  - Pop-up windows with description (HTML/CSS/JavaScript)

Emma Safarova 
   - Museum's observations
   - Analysis of 1st round interviews 
   - Interactive prototype for the first part of the interaction 


 Zhijiang Wang:
   - Supporting material
   - Initial literature review
 
 EVERYONE:
   - 2 workshops 
   - Preparation for prototype's demonstration
