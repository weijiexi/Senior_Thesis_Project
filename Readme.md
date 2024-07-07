# Senior Thesis Project 
<p align="center"> 

<img src="https://ucb-courses-materials.s3.us-east-2.amazonaws.com/images/senior-project/senior+project.jpg" width="950" height="606" style="width: 950px; height: 606px;">
</p>
<p align="center" >Meditation, 2024. Interactive painting, video in TouchDesigner, batik dye on fabric, electric paint, touch board kit, 24 x 36” and 5:00. </p>

<p align="center" >Meditation has two parts: on top is a batik painting, and below is circuitry made with a Touch Board. A projector is triggered to unveil dynamic 3D animation and sound as viewers interact by touching the center area of the canvas. This work aims to convey a serene and profound energy inspired by the natural world, encouraging viewers to immerse themselves in comfort, serenity, and meditation.</p>


  <p align="center" ><a href="https://www.youtube.com/watch?v=F6PyboU50sw" >
  <img src="https://ucb-courses-materials.s3.us-east-2.amazonaws.com/images/senior-project/Senior_project_video01.jpg" width="600" height="436" style="width: 600px; height: 436px;">
  </a></p> 
  <p align="left" ><a href="https://www.youtube.com/watch?v=S7fqfisucRM" >
  <img src="https://ucb-courses-materials.s3.us-east-2.amazonaws.com/images/senior-project/Senior_project_video02.jpg" width="600" height="367" style="width: 600px; height: 367px;">
  </a></p> 


## Artist Statement
### “Meditation” 2024
In my artistic journey, I am driven by a deep fascination with the convergence of tradition and innovation, seeking to bridge the gap between craftsmanship and technology. My latest endeavor manifests as an interactive painting that marries the intricate beauty of batik art with the dynamic possibilities of modern electronics. 

This artwork uses a Touch Board to trigger a projector, unveiling dynamic 3D animations and sound. This adds depth to the artwork, allowing viewers to participate actively in the experience. By encouraging interaction through touch, the installation creates a sense of connection and immersion, inviting viewers to explore the artwork.

The main visual element of this artwork is a personified, web-like abstract form, symbolizing the neural network of the brain and representing the intrinsic connection between humanity and the universe. The piece uses images of nebulae as the background and adds a fluid animation to enhance the richness of abstract forms and textures in the composition. The web-like abstract form symbolizes the intricate relationship between human thought and natural energy, echoing the fusion of the human spirit and natural energy during meditation.

My artwork explored the power of abstraction. Guided by intuition and experimentation, I relinquish control and allow the canvas to become a vessel for spontaneous creation. Each brushstroke and gesture becomes a meditation on the fluidity of form and the depths of the subconscious mind, which infuses the installation with tranquility and serenity, inviting viewers to immerse themselves in contemplation and introspection.

## Project: Touch and Mapping

Yes, the project tech part is based on: `touch`, and `mapping`.
-   **touch**: to use the touch board as a `MIDI Controller`;
-   **mapping**: to use the `MadMapper` to receive the note data from touch board, the `MIDI Controller`. 

### To Use The Touch Board As A MIDI Controller

The Touch Board can be used as a **MIDI controller** to send MIDI note data to Apple `GarageBand` or other creation software (the `MadMapper` in this project) that accepts external MIDI controllers. If one of the Touch Board's electrodes is triggered, the board sends the data to `GarageBand` (or, the `MadMapper`). Using the Touch Board is a great way to create a minimal interface to play your music or trigger the video on Madmapper.

### Set up the videos in MadMapper

The Touch Board can be used as a **MIDI controller** to send MIDI note data to `MadMapper`. Change the video's play settings to "Play the movie to the end of the loop and pause." Now, open the MIDI control settings in MadMapper. Select the video, then click the "Goto beginning" button, then touch the sensor on your wall. The "Goto beginning" button should now be grey and have something written across it, like "1/C2".

### The touch and mapping project

Drag and drop the video into the workspace of MadMapper. Then, map imagery and even sound simultaneously.

### Reference 

-   [How To Change The Code On The Touch Board With The Arduino IDE](https://www.bareconductive.com/blogs/resources/how-to-program-your-touch-board-with-the-arduino-ide)
-   [How To Use The Touch Board As A MIDI Controller](https://www.bareconductive.com/blogs/resources/how-to-turn-your-touch-board-into-a-midi-controller?_pos=1&_sid=e99a16923&_ss=r)
-   [Build An Interactive Projection Mapping Installation](https://www.bareconductive.com/blogs/resources/create-an-interactive-projection-mapping-installation?_pos=1&_sid=907338a91&_ss=r)

