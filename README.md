# CropDate

<div align='center'><img src='https://github.com/GrandeMan/CropDate/assets/114616062/1cdc09fb-19dd-49b6-9deb-5fd733d500d4' height='500' /></div>


CropDate is a concept for an agriculture app that provides updates on wholesale crop prices in Trinidad and Tobago. Users can view the prices and volumes of the available crops, they can also favourite crops to view them specifically. The app was inspired by the work of the AGRINETT team.


<hr/> 

## Goals
<div align='center'><img src='https://github.com/GrandeMan/CropDate/assets/114616062/5c5731eb-1564-474c-ae4a-a152f50d8dd8' alt='Lighthouse Report'/></div>

<br/>
Initially, this was going to be a frontend project. I set out to create a web app to showcase my skills as a graphic designer and developer, but the goals changed somewhere along the line. 
<br/>
<br/>

<details> 
  <summary>Backend Development</summary>
  <br/>
  <p>During development I thought it would be cool to display graphs of the changes in crop prices and volumes. At the time I was using an API made by the AGRINETT team for another app, this API only provided daily updates so I tried to get in touch with someone from the team, but I didn't get a reply. I felt like omitting the feature altogether, but the app felt unfinished (and I <i>really</i> wanted those graphs) so I decided to give making a server a try. In the end, I learnt about node, typescript, PQL, databases, cron jobs, deploying, and a <b>LOT</b> about debugging; but, most importantly, I got the graphs to work! You can <a href='https://github.com/GrandeMan/CropDate-server'>view the server repo</a> to see more.</p>
</details>

<details>
  <summary>Look & Feel</summary>
  <br/>
  <p>I set out to create clean code and a clean aesthetic. I used tailwind to style which is almost like another language if you aren't familiar with it, I enjoyed this part of the process because I could see my project coming together in real-time. I especially paid attention to the animations and the general flow of the app - it had to look good and be responsive. </p>
</details>

<details>
  <summary>Accessibility</summary>
  <br/>
  <p>WAI-ARIA was something that I made a point to apply. I knew what it was but I hadn't applied the knowledge much outside of forms so I saw this as an opportunity to learn how to implement it in a 'real' app. </p>
</details>

<details>
  <summary>PWA</summary>
  <br/>
  <p>This, in my opinion, was essential for the app to be considered a success. Maybe you're in a garden and want to check something on the app, but you're disconnected. It'd be frustrating if you, as a farmer in this case, wanted to view the last update and had to wait until you were next connected to the internet. That isn't an issue here, the app is downloadable and functional when offline. </p>
</details>








