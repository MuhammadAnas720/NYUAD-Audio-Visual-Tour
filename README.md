# Name: Audio-Visual Tour of the NYUAD Campus

**Project Link: **
https://muhammadanas720.github.io/NYUAD-Audio-Visual-Tour/

**Project Description:**

Is it possible to feel you are somewhere, by immersing in the sound of the place?

This project strives to create an experience where you can feel you are at a particular place, by listening to the sounds from the place. In our project, we provide an Audio-Visual Tour of the NYU Abu Dhabi Campus.

The motivation comes from the fact that because of the pandemic, more than half of the population has not been able to access the campus, a place they call their home. Hence, me and Ayesha came up with this project, where we take the user on an immersive virtual experience across the campus. Furthermore, the project isn't only designed for someone who is well aware of the campus, but also serves as a virtual tour for anyone who has not visited it before - a freshmen or a potential candidate.

The project starts with a homepage, which tries to capture the user attention through aesthetics, and a drone-shot video of the campus in background (which the user can also play if they wish to). The webpage then provides a brief instructions panel for first-time visitors. What follows are 3 sections of different category of locations on campus: Outdoors, Study Spots, and Dining and Fitness.

Each category provides an interactive map to the campus. This map contains, besides pinned locations it corresponds to, a 360-degree view of the location with-in, along with a brief description about the location and hyperlink to its page. It also allows user to use their geolocation to figure out their current location, or a feature to full-screen the map. Under these maps, the locations are also displayed in a card format, where a user can get sneak peak into the location, and when they hover over it, they get to exerience its sounds. It is when they click for these locations, that they are directed to the page of particular location.

This page contains a 360-degree view of the location, while what makes the project really important is the autoplay of the sound from the location. We believe this experiene of natural sounds from the location, coupled with an immersive view, provides user the experience of virtually being there at the moment. We also have an audio button on the page, which user can click to access controls of the audio. To add more to the experience, we have also provided a day and a night button to allow user to get a feel of the location at different times of the day.

The project also strives for a convenient user experience on this brillirant project. We achieve this with a side-navigation-bar at the top of homepage, and at all location pages. This serves as a menu of locations to visit for the user. They can just click on this sidebar icon, and get access to the category of locations, where they can go and choose one, or can even go further in the menu, select a location and get re-directed to its page. Hence, if you need a guide for the entire campus, scroll down to the page and experience all of campus. If you know a where you want to go, just select it from this menu, and you are there. We also provide a main navbar with very useful links to sections on the webpage, as well as to different pages of NYUAD, if user wants to explore more. Throughout, we also have a scroll to top button for added user experience.

**Process:**

The most integral part of the project is to create the audio experience that user immerses into. For this, we selected a list of most iconic and used spots on campus. We went to these spots, and recorded live sounds at the location from our phone. If the voices of particular people were prominent - we asked for their consents to be recorded. Because we wanted to provide the natural experience of being there at the location, about 95% of our sounds were the ones recorded at those particular locations. We then used Audacity and Premier Pro to edit the audios. An extensive effort was put into filtering out the various background noises, especially of wind at outdoor locations, by figuring out different frequencies that added noise.

A virtual tour wouldn't be complete without a map tour. For this we tried with implementing a map feature by ourselves. However, when with some extensive effort it seemed out of the scope, we explored different options online. We even reached out to different organizations that provides 3D maps for services they could provide, or perhaps even a quota for those. Finally, we found concept3d, which is a platform we used to make the immersive maps for our project. Since it was a trial (free) version, it came with its limitations.

For the 360-Degree views of campus locations, we captured at different locations, with the "google street view" app on our phones, to capture 360 images, without a 360-degree camera. We implemented these on our web, by adjusting them to 360-images using "momento 360".

Coming to the web implementation, our project exntensively relies on HTML, CSS, Javascript, and JQuery JS library. We uses JS in many features that would replicate similar features for different locations and audios. For example, it helps us implement the feature that when you hover over a particular location on the homepage, the audio related to particualr location starts playing. It also helps us in our side-navbar implementation. For the webpage pertaining to each location separately, we had to design 14 HTML pages separately, each pertaining to respective location - one for the day and one for the night.

**Result and Evaluation:**

In general, we were very satisfied with the implementation and final output of our project. It allowed us to accomplish what we intended in our initial planning for the most part. We do feel that the sound experience of listening to each location on campus provides a magical experience to the user. One could actively be watching the view that comes with, while listening to the sound, or could put the page in background while its audio plying, and feel they are at the prticular spot. For example, if you miss working at the library cafe, play its audio in the background and contine with your work. We belive that coupled with this audio experience, the user experience particularly makes an effort to provides an easy-to-use, seemless, and guided tour of campus.

One constraint that we had with web implementation was that inititally, instead of creating separate individual pages for each location, we wanted to create a template page, that displays and plays audio of the location, respective to the initial click. However, that meant transfer of data (variables) from one webpage to other (homepage to location page), recquiring use of server and back-end implementatio, which is out of the scope.

Besides, for the scope of the project, we restricted ourselves to 8 locations, and 14 different audios - each around 2 minute each. We believe the project has a potential to grow, both in terms of number of locations, and the length of audios.
