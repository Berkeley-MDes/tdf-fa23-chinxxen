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




