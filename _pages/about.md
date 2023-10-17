---
layout: about
title: Future Paradigms for Sustainable Making
permalink: /
subtitle:

# profile:
#   align: right
#   image: header.png
#   image_circular: false # crops the image to make it circular
#   address: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

{% include figure.html path="assets/img/header-cropped.png" class="img-fluid rounded z-depth-1" %}


Rapid prototyping has been a major research thrust in HCI and UIST, but the sustainability impact of rapid prototyping has not been thoroughly discussed.

This workshop will offer the UIST community its first opportunity to discuss the sustainability challenges and the research opportunities associated with sustainable rapid prototyping. We will explore key issues such as waste generation from intermediate prototypes, strategies for using sustainable materials, and circular prototyping (e.g., promoting the reuse of components). Additionally, we'll delve into knowledge-sharing infrastructures like open-sourcing hardware. Our objective is to pinpoint potential HCI research avenues that promote a more sustainable 'making' environment both inside labs and in wider contexts.

**This workshop will be held on-site as part of UIST on Sunday, October 29th. To join us, register for our workshop during [UIST registration](https://web.cvent.com/event/084853b8-9ccc-43ee-8438-78e1a744b086/summary).** Note: you do not need to submit any work prior to joining! Participation is open to anyone as long as they register. 


## Background and Goal
Over the past decades, democratized fabrication and electronic toolkits have proven to be a monumental driving force for innovation. Tools like 3D printers, laser cutters, Arduino, and CircuitPython are now common in research labs and makerspaces, drastically reducing the innovation cycle. However, this ease in rapid design iteration has introduced notable sustainability challenges.

The development of new products through rapid prototyping inevitably produces a large number of intermediate prototypes, such as 3D printed structures and custom PCBs. These intermediate prototypes are created to verify various aspects of our design but are not utilized in subsequent iterations—these one-off prototypes leave behind a significant amount of waste. Unfortunately, currently, there are no established ways to re-purpose or minimize the waste generated in this process. Additionally, bulk order leftovers, under optimized space management, and underdeveloped knowledge sharing infrastructures are also contributing to sustainability issues in various aspects of rapid prototyping.

This workshop aims to explore the sustainability issues linked with rapid prototyping and pinpoint HCI research paths for more sustainable "making" processes.

## Agenda
The workshop will consist of keynotes, demos, hands-on building, and brainstorming sessions, divided into six distinct activities. (More details to follow!)

| Activity    | Time (PDT) |
| -------- | ------- |
| Opening & Introduction  | 9:00-9:15   |
| Keynotes  | 9:15-10:15   |
| Coffee Break | 10:15-10:45     |
| Discussion Panel with Keynote Speakers | 10:45-11:15 |
| Brainstorm: Sustainability Challenges in Making    | 11:15-12:30    |
| LUNCH BREAK    | 12:30-13:30    |
| Collaborative Making Activity    | 13:30-14:30    |
| Coffee Break | 14:30-15:00     |
| Brainstorm: Tools and Future Technologies for Sustainable Making   | 15:00-16:00    |
| Closing & Future Plans | 16:00-17:00    |

<span> </span>

## Keynote Speakers
We are excited to announce our keynote speakers to our workshop: Gregory Abowd, Eric Paulos, and Kristin Williams.
<div class="row row-cols-1 projects pt-0 pb-3">
  {% include keynote.html 
  name="Gregory Abowd" 
  affiliation="Northeastern University" 
  url="https://coe.northeastern.edu/people/abowd-gregory/" 
  img="assets/img/abowd-g.jpg" 
  bio="Gregory D. Abowd is the Dean of the College of Engineering at Northeastern University, where he is also a Professor of Electrical and Computer Engineering with affiliate appointments in the Khoury College of Computer Sciences and the Bouvé College of Health Sciences. Prior to joining Northeastern in March 2021, Dr. Abowd was faculty in the College of Computing at the Georgia Institute of Technology for over 26 years, where he held the titles of Regents’ Professor and J.Z. Liang Endowed Chair in the School in Interactive Computing. His research falls largely in the area of Human-Computer Interaction with an emphasis on applications and technology development for mobile and ubiquitous computing in everyday settings. His research has introduced innovations in the classroom, the home, for stakeholders connected with autism, and sustainable forms of computing in everyday life. He has been the founding Editor-in-Chief for two major journals and is the most highly cited researcher in HCI and ubiquitous computing in the world, according to csrankings.org (the second two are both his former PhD students). Dr. Abowd is a Fellow of the ACM and an elected member of the ACM SIGCHI Academy. He was a 2009 recipient of the ACM Eugene Lawler Humanitarian Contributions within Computer Science and Informatics.  Dr. Abowd received the 2023 Lifetime Achievement Award for Research from ACM SIGCHI.  He earned his Bachelor of Science in Honors Mathematics (summa cum laude) from the University of Notre Dame in 1986 as well as a Master of Science (1987) and Doctor of Philosophy (1991) in Computation from the University of Oxford, where he attended as a Rhodes Scholar." 
  talk = "I have been speaking and writing about the idea of an Internet of Materials for nearly a decade. It started as a way to rethink Mark Weiser's vision of ubiquitous computing in a more modern context, with the same hopeful zeal that Weiser presented in his writings from the late 1980s and early 1990's.  I will summarize how that re-interpretation has inspired my work, and the work of a growing community, for nearly a decade. From those involved in the fundamental understanding of computation to those involved in the practical development and deployment of computation, the future seems bright.  We are moving towards a world of increased ubiquity of computation.  There appears to be no end in sight for the increased ubiquity of all things computational.  From a technical perspective, this is wonderful.  More recently, I have been forced to think about this vision through a different lens. When you reflect on the environmental impact of computation, and specifically the impact of how we manufacture, operate, and discard computational artifacts, there is an even more compelling reason to pursue the agenda of the Internet of Materials.  This unending proliferation of computation is dangerous to the health of our planet. We MUST begin questioning a lot of the assumptions on how to make, operate, and dispose of computational objects. This is no longer a journey for the 'visionaries' to play out their fanciful predictions for the future.  It is a mandate to address the fundamental hazards of our current trajectory towards ubiquitous computing. And I believe we can start to make strides by rethinking the goals of the maker community."%} 
  
  {% include keynote.html 
  name="Eric Paulos" 
  affiliation="UC Berkeley" 
  url="http://www.paulos.net/" 
  img="assets/img/paulos2.png" 
  bio = "Eric Paulos is the founder and director of the Hybrid Ecologies Lab, a Professor in Electrical Engineering Computer Science Department at UC Berkeley, Director of the Jacobs Institute for Design Innovation, Director of the CITRIS Invention Lab, a Co-Director of the Swarm Lab, and faculty within the Berkeley Center for New Media (BCNM). Eric developed some of the first internet telepresence robots in the early 1990s, one of the first smartwatch haptic messaging devices in 2002, coined the term 'Urban Computing' in 2004, created the first citizen science air quality sensors integrated into mobile phones in 2007, and created 'counterfuntional design' and 'unmaking' as major research themes within HCI and Design. Previously, Eric held the Cooper-Siegel Associate Professor Chair in the School of Computer Science at Carnegie Mellon University where he was faculty within the Human-Computer Interaction Institute with courtesy faculty appointment in the Robotics Institute. Prior to CMU, Eric was a Senior Research Scientist at Intel Research. Eric received his Ph.D. in Electrical Engineering and Computer Science from UC Berkeley. Eric is also the founder and director of the Experimental Interaction Unit and a frequent collaborator with Mark Pauline of Survival Research Laboratories."
  talk = "The access and growing ubiquity of digital fabrication has ushered in a celebration of creativity and 'making'. However, the focus is often on the resulting static artifact or the creative process and tools to design it. In this talk, I describe a post-making process that extends past these final static objects — not just in their making but in their 'unmaking'. By drawing from artistic movements such as Auto-Destructive Art, intentionally inverting well-established engineering principles of structurally sound designs, and safely misusing unstable materials, this talk will demonstrate an important extension to making — unmaking. Unmaking allows designs to change over time, is an ally to sustainability and re-usability, and captures themes of 'aura', emotionality, and personalization. I will also describe an exploration into the design of novel interactive electronic systems that leverage sustainable materials that are both dynamic and entirely decomposable."
  %}

  {% include keynote.html 
  name="Kristin Williams" 
  affiliation="Emory University" 
  url="https://www.cs.emory.edu/~kwil271/" 
  img="assets/img/williams-003.jpg"
  bio="Kristin Williams is an Assistant Professor of Computer Science in Emory University's College of Arts and Sciences. Her research focuses on making programming the Internet of Things approachable to casual end user programmers. This work builds on Kristin's longstanding interests in agency, DIY publishing, and access to information. In the past, Kristin has worked closely with community organizations to shape and evaluate assistive technologies for individuals with visual and cognitive disabilities, managed an archive of Soviet dissident literature on the political abuse of psychiatry, and created a 10+ year book project on Central Asian civil society as a Peace Corps volunteer in Kazakhstan. She has a PhD from Carnegie Mellon University's Human Compter Interaction Institute, an MS in Human-Computer Interaction from both Carnegie Mellon University and the University of Maryland, College Park and a BA in Philosophy from Reed College.  She was a 2021 EECS Rising Star, an NSF EAPSI Fellow, and an AAUW Career Development Grantee." 
  talk = "I research how we can make programming cutting-edge technologies so approachable anyone could imbue them with their own meanings and ways of life. Today, small groups use their material environment to organize and manage daily life in idiosyncratic ways that resist generalization. To fit its context, the Internet of Things (IoT) will need to be customizable, accessible, and sustainable. I work alongside communities to design, prototype, and develop this kind of IoT in a way that considers: How can IoT customization enable creative expression? How can lightweight design support approachable and accessible forms? How can IoT be sustainable for both the environment and the communities that adopt it?"
  %}
</div>

## Organizers
<div class="row row-cols-2 projects pt-3 pb-3">
  {% include people_horizontal.html name="Zeyu Yan" affiliation="University of Maryland" url="https://www.zeyuyan.com/" img="assets/img/zeyu.jpg" %}
  {% include people_horizontal.html name="Tingyu Cheng" affiliation="Georgia Institute of Technology" url="https://tingyucheng.com/" img="assets/img/tingyu.jpg" %}
  {% include people_horizontal.html name="Jasmine Lu" affiliation="University of Chicago" url="https://jasminelu.site/" img="assets/img/jasmine.jpg" %}
  {% include people_horizontal.html name="Pedro Lopes" affiliation="University of Chicago" url="https://plopes.org/" img="assets/img/pedro.png" %}
  {% include people_horizontal.html name="Huaishu Peng" affiliation="University of Maryland" url="http://www.huaishu.me/" img="assets/img/huaishu.jpg" %}
</div>

#### Suggested Readings on Sustainable Making

* Jasmine Lu, Beza Desta, K.D. Wu, Romain Nith, Joyce Passananti, and Pedro Lopes. 2023. ecoEDA: Recycling E-waste During Electronics Design. In Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology (San Francisco, CA, USA) (UIST ’23).
* Tingyu Cheng, Taylor Tabb, Jung Wook Park, Eric M Gallo, Aditi Maheshwari, Gregory D. Abowd, Hyunjoo Oh, and Andreea Danielescu. 2023. Functional Destruction: Utilizing Sustainable Materials’ Physical Transiency for Electronics Applications. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI '23). Association for Computing Machinery, New York, NY, USA, Article 366, 1–16. https://doi.org/10.1145/3544548.3580811
* Michael L. Rivera, S. Sandra Bae, and Scott E. Hudson. 2023. Designing a Sustainable Material for 3D Printing with Spent Coffee Grounds. In Proceedings of the 2023 ACM Designing Interactive Systems Conference (DIS '23). Association for Computing Machinery, New York, NY, USA, 294–311. https://doi.org/10.1145/3563657.3595983
* Marion Koelle, Madalina Nicolae, Aditya Shekhar Nittala, Marc Teyssier, and Jürgen Steimle. 2022. Prototyping Soft Devices with Interactive Bioplastics. In Proceedings of the 35th Annual ACM Symposium on User Interface Software and Technology (UIST '22). Association for Computing Machinery, New York, NY, USA, Article 19, 1–16. https://doi.org/10.1145/3526113.3545623
* Nivedita Arora, Vikram Iyer, Hyunjoo Oh, Gregory D. Abowd, and Josiah D. Hester. 2023. Circularity in Energy Harvesting Computational "Things". In Proceedings of the 20th ACM Conference on Embedded Networked Sensor Systems (SenSys '22). Association for Computing Machinery, New York, NY, USA, 931–933. https://doi.org/10.1145/3560905.3568106
* Ilan Mandel and Wendy Ju. 2023. Recapturing Product as Material Supply: Hover-boards as Garbatrage. In Proceedings of the 2023 ACM Designing Interactive Systems Conference (Pittsburgh, PA, USA) (DIS ’23). Association for Computing Machinery, New York, NY, USA, 564–579. https://doi.org/10.1145/3563657.3596128
* Katherine W Song, Aditi Maheshwari, Eric M Gallo, Andreea Danielescu, and Eric Paulos. 2022. Towards Decomposable Interactive Systems: Design of a Backyard-Degradable Wireless Heating Interface. In Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems (New Orleans, LA, USA) (CHI ’22). Association for Computing Machinery, New York, NY, USA, Article 100, 12 pages. https://doi.org/10.1145/3491102.3502007
* Katherine Wei Song and Eric Paulos. 2023. Vim: Customizable, Decomposable Electrical Energy Storage. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (Hamburg, Germany) (CHI ’23). Association for Computing Machinery, New York, NY, USA, Article 180, 18 pages. https://doi. org/10.1145/3544548.3581110
* Ludwig Wilhelm Wall, Alec Jacobson, Daniel Vogel, and Oliver Schneider. 2021. Scrappy: Using scrap material as infill to make fabrication more sustainable. Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems (2021). https://doi.org/10.1145/3411764.3445187
* Shanel Wu and Laura Devendorf. 2020. Unfabricate: Designing Smart Textiles for Disassembly. In Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems (Honolulu, HI, USA) (CHI ’20). Association for Computing Machinery, New York, NY, USA, 1–14. https://doi.org/10.1145/3313831.3376227
* Eldy S Lazaro Vasquez, Hao-Chuan Wang, and Katia Vega. 2020. Introducing the sustainable prototyping life cycle for digital fabrication to designers. In Proceedings of the 2020 ACM Designing Interactive Systems Conference. 1301–1312.
* Sunyoung Kim and Eric Paulos. 2011. Practices in the Creative Reuse of E-Waste. In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (Vancouver, BC, Canada) (CHI ’11). Association for Computing Machinery, New York, NY, USA, 2395–2404. https://doi.org/10.1145/1978942.1979292
* Ollie Hanton, Zichao Shen, Mike Fraser, and Anne Roudaut. 2022. FabricatINK: Personal Fabrication of Bespoke Displays Using Electronic Ink from Upcycled E Readers. In Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems (New Orleans, LA, USA) (CHI ’22). https://doi.org/10.1145/3491102.3501844
* Eli Blevis. 2007. Sustainable interaction design: invention & disposal, renewal & reuse. In Proceedings of the SIGCHI conference on Human factors in computing systems. 503–512.}

\* <i>Many more papers exist, not just in HCI, but also outside the traditional boundaries of interactive work, and this list is meant to inspire you to read these, search more, and engage with this topic.</i>

## Questions?
Feel free to e-mail [us](mailto:zeyuy@umd.edu).


<!-- 
Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
 -->
