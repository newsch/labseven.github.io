I am a team lead for the electrical and lights subteam on the Aquaponics build team. Aquaponics is a system for growing plants without soil (hydroponics) in a symbiotic envirnoment with aquatic animals. [Read more about it on Wikipedia.](https://en.wikipedia.org/wiki/Aquaponics) We are building one in a library shelf, to grow basil and other herbs with fish feeding into the system. The goal is to have a highly automated system with minimal human intervention between planting and harvest.
I lead the electical and lights subteam. We spec'd lights for the plants, an used an arduino to time the lights and watering pump. We dicovered that SMD5050 red and blue LEDs emit wavelenghts very close to chlorophil's peak absorbtion color, and specced LED strips appropriately. The arduino has a battery-powered Real-time Clock to keep time even if the power cuts out. We run the grow lights (red and blue) every day for 12 hours. Because the system is in a very public space, light and sound polution were a big consideration in the design, as were aesthetics. For this, we added RGB accent lights that I am tuning to make the plants look the best at every time of the day. In the morning it glows a soft turqouse, after the grow lights switch on, it shines only green to counteract the bright red and blue from the growlights. In the early to late evening, it switches back to the soft turqouse and slowly dims until midnight, when it only shows a faint "nightlight" mode. To find the proper settings, I visited the library throughout the day, and tweaked the settings to make it the most pleasing. The next step is to add water sensors for leaks, and a raspberry pi to allow remote administration. It will have a public facing status page, possibly with a camera feed, and an administration console for setting light settings and sms alerts for leak sensors and ph levels. I have begun mockups of the layout to make it intuitive and minimal.