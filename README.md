# Report 3: Designing My Own Phone Stand - Grasshopper + 3D Print - Week of 09/14/2023 #

This week, I want to challenge myself. Even though I have 0 experiences with modeling with grasshopper before this class, but I have an idea that I really want to create. So, I designed and built a brand-new phone stand from scratch, tailoring it to my own specifications. After creating the CAD models, I 3D-printed prototypes to visualize the end result and conduct user testing.

### Design Prompt
I'm looking to design a phone stand that addresses a specific problem I've been struggling with. While I don't usually need a phone stand during the day, however, **I find it hard to put my phone down when I'm in bed**. Despite feeling exhausted, I often catch myself aimlessly scrolling through my device. This habit has negatively impacted my sleep quality and even led to occasional insomnia. **My goal is to create a design that will help me disconnect from my phone more easily while in bed.**

### Sketching
During the ideation phase, it occurred to me: **why not create a bed for my phone?** Personifying my phone in this way could serve as a **visual reminder that just as my phone needs rest, so do I**. With this concept in mind, I grabbed my iPad and started sketching out various designs and ideas.
![Untitled_Artwork 17](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/d68aad90-9ebd-4cd5-8f95-990971e13973)
I ultimately chose to go with Style 1, primarily because it would be **more material-efficient and time-saving** to 3D print.

### Modeling with Grasshopper 

**Mattress/Bedboard**
![1](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/d2b5b239-6c23-4766-af62-56ce45197fde)
First I used **navigation** + **Construct Domain** + **Rectangle** to get the shape of the mattress. 
![2](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/c568c1b5-678c-49c8-98a2-36423a1d1e51)
Then I used **fillet** to give it a soft edge.
![3](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/10b0b3e0-5cfe-43f4-843a-f5976c2a9eb5)
Then I **Extrude** the filleted rectangle. 
![4](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/616323ec-f02a-4814-bf73-3b1b88a366d4)
I used **Cap Holes** to build the top plane and bottom plane of the mattress, and make it solid. Then I used **FilletEdge** to make it softer.
![1-5](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/eca7ecf2-6b32-4480-8498-27ef62b7a109)
![1-6](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/cde1c4c5-4f63-4be7-b7a0-73e525340d8d)
I used **Debrep** + **CurveMiddle** + **Deconstruct** + **SortList** + **List Item** + **Curve Midddle** + **Move** to find the plane of the Bedboard. 
![1-7](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/31e7d637-2f6c-4cf4-a539-bf7904993f25)
I used **Rectangle** + **Explode** + **Cull Index** + **Join Curve** + **Filllet** to get the contour of the bedboard.
![1-8](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/9293c7d1-3e70-41a6-8cef-ae6d540f3092)
![1-9](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/80584dc0-9263-4867-8cca-33eb86ad993d)
![1-16](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/a94baf8b-87af-4884-bccb-3deb4d7fbbd9)
Then I used **Boundary Surface** + **Extrude** to get the thickness of the bedboard.
![1-10](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/81dbad6a-d7ce-4022-ae8a-8c89b39e116f)
I **Fillet** the edge to get the soft curve.
![1-11](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/3d3b5656-2f2e-4692-b124-1803fa6249fd)
Then I used **SolidUnion** to combine the mattress and the bedboard.

**Bed Legs**
![1-13](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/e43d16df-4662-40bb-b74d-385f7db806f5)
I used **Navigate** + **OffsetCurve** to find the four center point of the four bed legs. 
![1-14](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/810ded81-1d8e-4866-84bd-f9757a2ef345)
I used **Discontinunity** + **Move** + **Line** to make the center line for all the four legs.
![1-15](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/8c6fcd0c-3e20-4728-a982-869196726321)
Then I used **Pipe** and give it a **Fillet** to make the rounded ends. 

**Pillow**
![1-16](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/3666abd3-1d66-4d19-a2f3-32d0fb0d4d81)
![1-17](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/0a50f8ee-014e-44a4-8d7d-f56f0669e1bd)
![1-18](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/afa217fc-ac06-4afb-8fb7-aa94597d20f0)
![1-19](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/bee2ff60-7b0c-43f0-a9d9-50d81df3079f)
![1-20](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/dd30638f-23c3-449a-a014-213e6a8d3ed4)
![1-21](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/19d3f7b7-819f-49d1-9a0c-87fe532855c0)
![1-22](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/3d5dba0e-fea5-4360-8e3a-802f229fa565)
![1-23](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/81abfc80-752f-4174-aa98-c8d1bb5a011a)
<img width="1295" alt="Screen Shot 2023-09-13 at 8 00 45 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/6818c8e9-8492-4966-b9e0-cc7bb18166f4">
This is how I made the pillow.

**Duvet**
![1-24](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/5a0255c6-86e1-4058-bb14-95386ef19c8a)
![1-25](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/ee09f38a-fec4-45ac-95a7-e4b54dc31a37)
![1-26](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/474e23f1-0122-48c6-a238-adbb0f085180)
![1-27](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/5c3b2f9a-82f5-455a-b184-b6af416c39c0)
![1-28](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/2944f323-878e-4bdc-9730-d2498cb59625)
<img width="1382" alt="Screen Shot 2023-09-13 at 8 00 35 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/9a9c5943-7253-44c9-a6e5-04b39440ea31">
This is how I made the duvet.

### 3D printing
![IMG_6956](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/55280a2a-4773-4082-835f-8d9e8f9e58b7)
![IMG_6955](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/b93765af-3ce2-4ad2-9dea-c1b8a974e174)
I tried to print the duvet, but it filed. The machine stopped during the middle and I have to restart it.

![IMG_6954](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/21bdcfa7-b8a0-4497-9b72-246a1671fbb9)
I printed the bed and the leg seperatly, and glue them together. So do not need a lot of support materials at the bottom. Also if I print them together, the staff told me that it is 99% going to failed.
![IMG_6984](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/17659458-2a4a-4c2e-a16c-4bf49ff80a28)

![IMG_6985](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/132975d8-d975-486e-bdf8-4d70b8709bdf)
Showcase! Using it right now(waiting for the duvet)!


### Conclusion

Crafting my CAD model using Grasshopper was a journey, from beginning to end. At first I faced a learning curve since I had familiarity with the softwares various tools and functions. This posed challenges that sometimes felt overwhelming. I wasn't alone in my pursuit of a design. Thankfully I had access to guidance from sources. Online tutorials and forums helped me understand features while my peers shared hands on advice based on their experiences. The MakerPass Staff also provided expert knowledge offering suggestions for design and printing best practices.

Navigating through these challenges was both. Enriching. Overcoming each obstacle and finding answers to my questions contributed to my growing proficiency in using Grasshopper. By the end of the project not did I successfully create an functional model but I also developed a newfound appreciation, for the intricacies of CAD design. The outcome was incredibly fulfilling validating all the time and effort invested. Alongside achieving my goal the entire process turned out to be immensely enjoyable—a combination of creativity, problem solving skills and technical expertise that made the final result even more satisfying.

Engaging in the process of 3D printing brought me joy even though it wasn't smooth sailing. There was a moment when I faced a setback during the printing process, which was a bit disheartening. However I believed that the issue was more related, to the printer itself than any flaw in my design. This gave me the motivation to keep going. After troubleshooting and making adjustments I finally managed to print my physical model. Holding the outcome of my efforts, in my hands was an exhilarating experience. It felt incredibly rewarding to go from design sketches to a three dimensional object. This milestone also presented an opportunity for me to conduct tests and see firsthand how well my design addressed the problems I aimed to solve.

The entire journey, starting from the concept and culminating in holding the product was a satisfying amalgamation of creativity, technical proficiency and problem solving skills. Experiencing that "aha moment" when my concept materialized into something was undoubtedly one of the highlights of this journey – it emphasized the value of every challenge and setback I overcame along the way.

### Speculation

**Rhino and Grasshopper**
- Rhino is a software, for creating CAD models. 
- Grasshopper on the hand is a plugin for Rhino that enables designers to build geometries using visual programming eliminating the need, for coding.

**Human-Centric Design**
Flexible spaces that can adjust to evolving requirements, such, as lighting and layout are made possible by design. Thoughtful design promotes enhanced interaction by incorporating seating arrangements and communal areas. Collectively these components contribute to the creation of eco socially engaging environments.

**Engineering Advancements**
Grasshopper improves the field of engineering by optimizing resource utilization minimizing mistakes and expediting the processes of prototyping and testing. This software assists engineers, in determining material requirements promptly rectifying design flaws and swiftly iterating through prototypes to conduct efficient testing.

**Intersection with AI**
The combination of AI and Grasshopper enhances the field of design and construction by facilitating design through the use of machine learning automating construction tasks and optimizing designs with AI algorithms. This ultimately results in projects being completed efficiently accurately and expeditiously. 


---

# Report 2: Solving Problem - Ideate/Design with Digital Tool - Week of 09/07/2023 #

This week, I started to playing around and developed the given design file.  To start with, one biggest issue I realized from last week's lasercut model is that **the phone holder will coverup the front screen of the phone, making user unable to access their phone while using the phone holder**.

![ffe727c92f5bb3e43f381f9bf3d61ed9](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/6c3a30d8-6356-40dd-ab6f-9ba728b1492b)

### Sketching 
From this observation, I started to sketch out a few design solutions that could help improve the issue. 
![Screen_Shot_2023-09-05_at_11 07 34_PM](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/4193682e-a3ff-4e6e-a317-86f28530f6aa)

### Modifying the Model
<img width="1728" alt="Screen Shot 2023-09-05 at 10 11 44 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/ae7b61ea-dc88-4e24-b9bd-524b59928163">

First I adjusted the screen void height to 83, which seems like there will be no void from blobking the phone, but soon I realized that this might **resultes in unsecure locking**, the phone might fall off from the front.

<img width="1728" alt="Screen Shot 2023-09-05 at 10 12 05 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/8fa6e0e7-4350-406c-af6c-e48e16de3263">

Then I adjusted the screen void height to 78, with **little bit of void**, and I measure my phone that this void height will not cover up any phone screen, will only hold the phone securely by **locking the bezel**. I am satisified. 

<img width="1728" alt="Screen Shot 2023-09-05 at 10 35 09 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/ed250336-352f-4223-97e1-d94b5ea77149">

Then I start thinking that the **original spacing for the supports are too narrow**, which from first week's lasercut model, the phone might **tilted**. So, I adjusted the spacing to 0.35, giving the support more stability for the phone.

<img width="1728" alt="Screen Shot 2023-09-06 at 12 29 29 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/7f129320-33be-4ada-b904-4646f8aec489">

Soon I realized that I usually like to use phone stand when I watch TikTok videos, so I wish this **phone stand can also held the phone vertically**. I was not pro at Grasshopper, took me a few hours trying to get the top void be cutted out, I then try to bake the models, and trim it in Rhino.

<img width="1728" alt="Screen Shot 2023-09-06 at 12 30 47 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/5ac5bf74-d27c-465e-98fe-e315a8f3cbaf">
<img width="1728" alt="Screen Shot 2023-09-06 at 12 30 47 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/406ca983-f358-4399-bbe1-32a64862731a">
<img width="1728" alt="Screen Shot 2023-09-06 at 12 31 27 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/4486e83c-66f0-428a-a618-6ae3ff4c3a2b">
I trimmed the top void with shape make 3D and Boolean 2 Objects. 

<img width="1728" alt="Screen Shot 2023-09-06 at 12 31 51 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/44680ed4-94ab-4c11-84c0-e3cf9b38639d">
<img width="1728" alt="Screen Shot 2023-09-06 at 12 35 12 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/238087c1-7b73-48b1-b2dd-8e1afb6d1256">
Then I added on the filletedge for the shapes to make it looks less sharp and more user-friendly. 

<img width="1728" alt="Screen Shot 2023-09-06 at 12 40 15 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/b8a2dccd-acfc-4d7c-b817-111fdfc3cabd">
I exported the Make2D contour of the four lasercut pieces into Ai with the correct size. 
<img width="1728" alt="Screen Shot 2023-09-06 at 12 43 48 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/e0a232ea-17ec-4c81-ac06-fcad81ff578d">

### Lasercut
![IMG_6705](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/4a4d857b-4f7b-46d2-adbc-777064016e9f)
![IMG_6707](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/28eb6fe1-8ad9-45c5-a270-1f0526fc9466)
![IMG_6708](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/0500f964-00a8-4800-a386-890bfa2e136a)
![IMG_6709](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/0866d7d2-4b58-4af6-b1fe-629fc681d1b6)

### Reflections

This week was centered around iterative refinement of the phone holder design, particularly addressing the critical issue of screen obstruction noted in the last week's lasercut prototype. My first design alteration involved raising the screen void height to 83 units; although this eliminated screen obstruction, it compromised device stability. A subsequent fine-tuning to a height of 78 units achieved a satisfactory balance between screen visibility and secure bezel-locking. The support spacing was also adjusted to 0.35 units to correct the tilting issue observed in the initial model. In addition to horizontal viewing, I wanted the holder to support vertical orientation, particularly for applications like watching TikTok videos. Despite my limited expertise in Grasshopper, several hours were invested to modify the top void. Eventually, I opted to bake the model and perform the trim operation in Rhino, employing the 'Make 3D' and 'Boolean 2 Objects' functionalities. Filleted edges were introduced to mitigate any sharpness, enhancing user safety. Finally, the revised 2D contours of all lasercut pieces were exported into Adobe Illustrator to ensure dimensional accuracy for subsequent fabrication. Although the week presented its set of challenges, especially in Grasshopper, it was overall a productive period that has moved the project in a positive direction.

### Speculations

During my undergraduate education, I frequently engaged with both Rhino and Grasshopper as integral components of my design toolkit. I found that Grasshopper presents a steeper learning curve than Rhino, given its precision-oriented capabilities. Historically, I gravitated towards SolidWorks for tasks demanding high levels of accuracy. Looking ahead, I anticipate the integration of artificial intelligence to facilitate automated design recommendations. I also foresee the standardization of real-time material stress analytics and the incorporation of virtual reality for more immersive prototyping and user experience evaluations. Generative design, an emerging trend as of 2021, offers promising avenues for automating optimal design solutions through constraint-based inputs, thereby significantly enhancing the design workflow.


---

# Report 1: Learnings and Experiences in Makerspace - Week of 08/31/2023 #


### Exploring and Learning
This week, I primarily delved into operating the **lasercutter** in the makerspace, while also acquainting myself with the various tools available there. As a result, walking into the makerspace no longer leaves me feeling lost or out of place. My prior experience with Rhino and Grasshopper during my undergrad studies made the software aspect of this week's project not much difficulty.

### Assignment Collaboration 
In this assignment, I worked together with a girl from the MDes program, whose name is Stephanie. We first opened the 'make flat 3dm file' for the phone stand provided in class using **Rhino**, and then imported it into **Adobe Illustrator**.

![IMG_6207](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/02437da0-3bf0-4d35-8642-2944c6eda30e)

### Working on Lasercutting the Phone Stand
Because the plywood sold in the makerspace is **30”x18”**, there is enough space to print phone stands for four people. So, Stephanie and I, along with two other MDes students, adjusted the file together in Illustrator. We created a board the same size as the plywood and copied five sets of the phone stand design inside it. One set is for backup, in case some students' lasercut fails. 

![IMG_6205](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/38f96647-014e-420c-8f4b-8f718d6c5a4f)
![IMG_6210](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/df0ef128-47c1-4d8a-9929-42ffab79f822)

The plywood board we used was 1/4" thick. However, a fellow student warned us that he had issues with cutting all the way through just yesterday. To mitigate this, we adjusted the lasercutter settings to treat the material as if it were 0.255" thick, aiming to ensure a complete cut. Despite this precaution, we encountered some issues because the plywood board was not perfectly flat; it was somewhat curved. As a result, a few cuts didn't go all the way through.

![IMG_6213](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/4d712cee-7d26-4632-896b-221782accd56)
This is mine part, which is successful cutted.

### Personal Reflection
During my undergraduate studies, I completed many projects using a lasercutter. However, the system at RISD required student monitors to operate the lasercutter, as students weren't allowed to run the machine themselves. We had to submit our files to these trained monitors, who would then perform the cuts. On the other hand, I also had some experience at Brown University's design lab, where I received the necessary training to operate the lasercutter independently. So, familiarizing myself with the Makerspace's lasercutter wasn't too challenging for me. Nonetheless, an invaluable lesson I learned from this latest project is the **importance of running a test piece** before proceeding with the final cut. Lastly, one thing that made me happiest about this week's assignment is the good atmosphere among the **MDes students**. Although we may struggle when encountering things we don't know how to do, the mutual help among classmates makes me feel very warm. 

![ffe727c92f5bb3e43f381f9bf3d61ed9](https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/6c3a30d8-6356-40dd-ab6f-9ba728b1492b)

### Speculation
I believe laser cutting technology has a lot of room for future development, including 3D multi-axis CNC laser cutting technology and automated, unmanned laser cutting technology. 3D laser cutting technology helps to steer the field towards more precise applications. Furthermore, 3D laser cutting technology is more efficient and has a broader range of applications. Moreover, as a form of processing technology, automation and unmanned operation in laser cutting technology are necessary for its development. At the same time, the application of computer network technology makes automation and unmanned operation in laser cutting technology possible. The current market demand for this technology is also continuously increasing, driving laser cutting technology to gradually realize automation and unmanned operation.

### Sketches, Drawings, and Diagrams
<img width="1728" alt="Screen Shot 2023-08-31 at 12 05 12 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/cf8afdf1-1507-41b9-95fb-8b7c47803a01">
<img width="1728" alt="Screen Shot 2023-08-31 at 12 02 58 AM" src="https://github.com/Berkeley-MDes/tdf-fa23-chinxxen/assets/143020823/6967d0d7-14cb-4ba8-a0f7-c7fbf4c4597b">




