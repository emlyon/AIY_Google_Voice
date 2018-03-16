https://aiyprojects.withgoogle.com/voice
<br>

<b>MATERIEL COMPLEMENTAIRE</b>
- Raspberry Pi + carte SD (micro)
- Câble HDMI
- Clavier + souris
- Câble micro USB pour alimentation
- Compte Google Cloud (grauit 12 mois)
- Scotch double face
- Connexion internet
<br>

<b>ALLER PLUS LOIN</b>
- Customiser de la boite en carton à la laser
- Customiser la démo "assistant_library_demo.py" pour interpeller l'AI avec "Okay, Martine" en plus de "Okay, Google" (Chapitre 6 - step 8)
- Customiser la démo "assistant_library_demo.py" pour interpeller l'AI en tapant des mains en plus de "Okay, Google" (Chapitre 6 - step 8)
- Créer des actions avec IFTTT https://ifttt.com/google_assistant
- Ajouter des sensors et donc de nouvelles actions (attention soudures)
- Passer le google assistant en français / liens à explorer:<br>
https://github.com/google/aiyprojects-raspbian
https://github.com/googlesamples/assistant-sdk-python
https://forums.pimoroni.com/t/google-aiy-voice-kit-change-language/6397/3
<br>

<b>CHALLENGES</b>
- Comment afficher l'image de la Raspberry Pi sur son ordi ?
- Comment laisser la démo "assistant_library_demo.py" active lorsqu'on n'utilise pas de terminal ?
- Traduire le tuto en français ? Hum.
- Création du compte Google Cloud: coordonnées bancaire demandées
<br>

<b>TIPS</b>
- Les démos se trouvent dans le dossier "examples" -> "voice".<br>
exemple commande: "src/examples/voice/assistant_library_demo.py
<br>

<b><font color="5fa9f9">LIST OF MATERIALS</b>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/materials.jpg" width="600">
</p>
Open the box and verify you have all of the necessary components in your kit. You’ll also need a couple of tools for assembly.<br>

IN YOUR KIT
1. Voice HAT accessory board (×1)
2. Voice HAT microphone board (×1)
3. Plastic standoffs (×2)
4. 3” speaker (wires attached) (×1)
5. Arcade-style push button (×1)
6. 4-wire button cable (×1)
7. 5-wire daughter board cable (×1)
8. External cardboard box (×1)
9. Internal cardboard frame

NOT INCLUDED
- Raspberry Pi 3 (×1)
- SD card (×1)
- Scotch tape

<b>TUTORIAL</b><br>




<b>1. ASSEMBLE THE HARDWARE</b>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-1.jpg" width="600">
</p>
<p align="left">
1/ Find your Raspberry Pi 3 and the two plastic standoffs that came with your kit.<br>Insert the standoffs into the two yellow holes opposite the 40-pin box header on your Raspberry Pi 3. They should snap into place.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-2.jpg" width="600">
</p>
<p align="left">
2/ Take your Voice HAT accessory board and attach it to the Raspberry Pi 3 box header.<br>Gently press down to make sure the pins are secure. On the other side, press down to snap the spacers into place.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-3.jpg" width="600">
</p>
<p align="left">
3/ Find the speaker with the red and black wires attached. Insert the speaker’s red wire end into the “+” terminal on the Voice HAT blue screw connector.
<br>
Do the same for the black wire end into the “-” terminal. At this point, they should be sitting there unsecured.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-4.jpg" width="600">
</p>
<p align="left">
4/ Now screw the wires in place with a Phillips “00” screwdriver.
<br>
Gently tug on the wires to make sure they’re secure.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-5.jpg" width="600">
</p>
<p align="left">
5/ Find the 4-wire button cable: it has a white plug on one end and four separate wires with metal contacts on the other.
<br>
Insert the plug into the white connector labeled “Button” on the Voice HAT board.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-6.jpg" width="600">
</p>
<p align="left">
6/ Find the Voice HAT Microphone board and the 5-wire daughter board cable from your kit (pictured).
<br>
Insert the 5-wire plug into the Microphone board.
</p><br>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/hardware-7.jpg" width="600">
</p>
<p align="left">
7/ Plug the Microphone board to the Voice Hat board using the white connector labeled “Mic.”
</p>
<br><br>




<b>2. FOLD THE CARDBOARD</b><br>
<b>2.1 BUILD THE BOX</b>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/box-1.jpg" width="600">
</p>
<p align="left">
1/ Now let’s build the box. Find the larger cardboard piece with a bunch of holes on one side (pictured).
<br>
Fold along the creases, then find the side with four flaps and fold the one marked FOLD 1.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/box-2.jpg" width="600">
</p>
<p align="left">
2/ Do the same for the other folds, tucking FOLD 4 underneath to secure it in place.
<br>
Easy! Now set it aside.
</p>
<br>

<b>2.2 BUILD THE FRAME</b>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-1.jpg" width="600">
</p>
<p align="left">
1/ Find the other cardboard piece that came with your kit (pictured). This will build the inner frame to hold the hardware.
<br>
Fold the flaps labeled 1 and 2 along the creases.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-2.jpg" width="600">
</p>
<p align="left">
2/ The flap above the 1 and 2 folds has a U-shaped cutout. Push it out.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-3.jpg" width="600">
</p>
<p align="left">
3/ Then fold the rest of the flap outward.
<br>
Fold the section labeled FOLD UP so that it’s flush with the surface you’re working on. There’s a little notch that folds behind the U-shaped flap to keep it in place.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-4.jpg" width="600">
</p>
<p align="left">
4/ The U-shaped flap should lay flush with the box side.
<br>
At this point, the cardboard might not hold its shape. Don’t worry: it’ll come together once it’s in the box.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-5.jpg" width="600">
</p>
<p align="left">
5/ Find your speaker (which is now attached to your Raspberry Pi 3).
<br>
Slide the speaker into the U-shaped pocket on the cardboard frame.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/frame-6.jpg" width="600">
</p>
<p align="left">
6/ Turn the cardboard frame around.
<br>
Take the Pi + Voice HAT hardware and slide the it into the bottom of the frame below flaps 1 + 2 (pictured).
<br>
The USB ports on the Pi should be exposed from the cardboard frame.
</p>
<br><br>



<b>3. PUT IT ALL TOGETHER</b>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-1.jpg" width="600">
</p>
<p align="left">
1/ Let’s put it all together!
<br>
Take the cardboard box you assembled earlier and find the side with the seven speaker holes.
<br>
Slide the cardboard frame + hardware into the cardboard box, making sure that the speaker is aligned with the box side with the speaker holes.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-2.jpg" width="600">
</p>
<p align="left">
2/ Once it’s in, the Pi should be sitting on the bottom of the box.
<br>
Make sure your wires are still connected.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-3.jpg" width="600">
</p>
<p align="left">
3/ Check that your ports are aligned with the cardboard box holes.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-4.jpg" width="600">
</p>
<p align="left">
4/ Find your arcade button and set it into the top of your cardboard box.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-5.jpg" width="600">
</p>
<p align="left">
5/ On the other side, screw on the washer to secure the button in place.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-6.jpg" width="600">
</p>
<p align="left">
6/ Now let’s hook the button up. Find the four colored wires with metal contacts connected to the Voice HAT board.<br> Connect the wires in the positions indicated by the image. Check the next step for another view.<br>
<br>
<i><b>Important:</b> Wire color position matters! Check the next step to make sure your wires are correctly placed.</i>
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-6-1.jpg" width="600">
</p>
<p align="left">
7/ Here’s another view to make sure your wires are correctly connected.
<br>
Looking at the small crown logo (the base of the crown facing toward you), the wires should be connected at these locations:
<br>
Blue: bottom left<br>
Red: bottom right<br>
Black: top right<br>
White: top left<br>
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-7.jpg" width="600">
</p>
<p align="left">
8/ The next step is attaching the microphone board to the cardboard.
<br>
We’re using double-sided tape here, but your standard-issue scotch tape works fine too.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-8.jpg" width="600">
</p>
<p align="left">
9/ Line up the microphone board so the mics (the white boxes on the ends) are sitting aligned with the cardboard holes for maximum listening capability.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-9.jpg" width="600">
</p>
<p align="left">
10/ Give it a turn and check that your mics are aligned correctly.
</p>
<p align="left">
  <img src="https://aiyprojects.withgoogle.com/static/images/aiy-projects-voice/assembly/together-10.jpg" width="600">
</p>
<p align="left">
11/ Well done! Time to close it up.
</p>
<br><br>


<b>4. GET THE VOICE KIT SD IMAGE</b> --> <i>Skip this step?</i><br><br>
You’ll need to download the Voice Kit SD image using another computer. Both of the next steps can take several minutes for your computer to complete, so while you're waiting, get started on "Assemble the hardware" in the next step.
<br><br>
Get the <a href="https://dl.google.com/dl/aiyprojects/aiyprojects-latest.img.xz">Voice Kit SD image</a>.
<br><br>
Write the image to an SD card using a card writing utility using <a href="https://etcher.io/">Etcher.io</a>.
<br><br>


<b>5. CONNECT & BOOTH THE DEVICE

<br><br>
