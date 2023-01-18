---

title: Literature Review

date: 2022-11-22

tags:

---
# Literature Review

Existing Games
- Osu! - https://osu.ppy.sh/home
- A free rhythm game developed by Dean Herbert 
- Written using C# on the .NET Framework and originally designed for windows users
- All beatmaps in the game are community made and have different game modes which can be combined with additional modifiers such as increasing/decreasing difficulty. The standard beatmap contains hit circles, sliders and spinners and the goal of the game is to hit these in time with the music. These beatmaps and your score is ranked across the world 
- The most common way to play the game is using a tablet or computer mouse to control the movement of the cursor and is usually paired with a keyboard.
- Punch out Wii 
- A boxing game developed in 2009 as a reboot of an earlier version. 
- Game requires you to react to your opponents reflexes and dodge/attack as you see fit.
- Originally played on the SNES control scheme where you press certain buttons and your player reacts accordingly. Can also be played using the Wii controllers by swinging the remote. The least favourable way to play is using the Wii balance board and dodging the punch will be done by actually performing the dodge movement. 
- Mario Tennis Aces - 
Sources: 

Punch out: 
https://www.thegamer.com/games-best-motion-sensor-controls-ranked/

Motion Input Technologies
Xbox Kinect
- Older versions used differences in colour and texture to distinguish objects from their backgrounds.
- In newer versions, the camera transmits near-infrared light and measures its “time of flight” after it reflects off the objects. This reduces the impact of ambient light on object detection, since the sensor isn't designed to register visible light resulting in less false positives. Information is encoded in the near-IR light. As that information is returned, some of it is deformed, which helps to generate a finer image of the texture of 3D objects, not just depth. Kinect can distinguish depth within 1cm and height/width within 3mm. 
- Kinect tracks the distances between 48 points of your body throughout the game, analysing the data 30 times per second (using “time of flight”)
- Also has language processing capabilities.
- $120

Intel RealSense Models
- Vulnerable to other noise in the environment from other cameras or devices emitting infrared
- Depth camera meaning it can see not only the 2D details of a scene but can calculate how far away from the camera every pixel is.
- Stereoscopic (D400 model) compares two images from two sensors in the camera with different points of view. The shift between the same point in the image can be used to determine depth. Maximum resolution depth of 1280 x 720. Ideal for projects requiring wide field of view.
- LiDAR (L515 model) shines laser light and measures the time of flight taken for the light to be reflected back to the camera. Ideal range of 0.2m – 9m
- Coded light (SR305 model) projects patterned light and evaluates how the pattern deforms over time.  Ideal for short ranges < 1m indoors. 640x480 resolution at 60fps
- ~$160

Occipital Structure Sensor
- iPad-mountable structured light scanner, projects a unique infrared pattern of dots. Infrared camera uses the pattern of dots to vizualize the shape and distance of objects (same as Kinect)
- $379

Orbecc Astra
- 640x480 depth resolution, 0.6m-8.0m range, 30fps 
- $165

Sources
- https://www.wired.com/2010/11/tonights-release-xbox-kinect-how-does-it-work/ 
- https://www.jameco.com/Jameco/workshop/howitworks/xboxkinect.html 
- https://www.intelrealsense.com/beginners-guide-to-depth/#:~:text=The%20Intel%C2%AE%20RealSense%E2%84%A2%20SR300%20line%20of%20devices%20are,power%20of%20the%20light%20emitted%20from%20the%20camera%29. 
