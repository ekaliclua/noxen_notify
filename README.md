[![Join our Discord](https://files.sincity-rp.fr/f.php?h=313X1QVS&p=1)](https://discord.gg/6yZB4YwPdw)

## [Join Us on Discord](https://discord.gg/6yZB4YwPdw)

Elevate your notifications with **Noxen Notify** – a simple, standalone, and highly customizable notification system, perfect for all your in-game needs and beyond.

With **Noxen Notify**, you get to choose exactly where and how your notifications appear on the screen. Whether you prefer a subtle approach or a more attention-grabbing display, our tool offers complete flexibility to match your style and preferences.

### 📢 **Key Features:**
- **Custom Positioning:**
  Select the perfect spot for your notifications:  
  🖼️ *Top-left*  
  🖼️ *Top-right*  
  🖼️ *Bottom-left*  
  🖼️ *Bottom-right*  
  🖼️ *Center-top*  
  🖼️ *Center-left*  
  🖼️ *Center-right*  
  🖼️ *Center-bottom*  
  You're in control!

- **Colors Tags:**
  Choose your best colors to beautify your content:

  `~r~`: *Red*  
  `~g~`: *Green*  
  `~b~`: *Blue*  
  `~y~`: *Yellow*  
  `~t~`: *Menu Grey*  
  `~o~`: *Orange*  
  `~p~`: *Purple*  
  `~q~`: *Pink*  
  `~m~`: *Mid Grey*  
  `~l~`: *Black*  
  `~d~`: *Blue Dark*  
  `~w~`: *Reset*  
  `~s~`: *Reset*  
  `~n~`: *Line Break*  
  `~h~`: *Bold*  
  `~bold~`: *Bold*  
  `~italic~`: *Italic*  


- **Standalone:**  
  No dependencies required – **Noxen Notify** works on its own and can be easily adapted to any server.

- **Highly Customizable:**  
  Trigger notifications using the event `noxen:notify` with parameters:
  - `title`: Title of the notification
  - `message`: Content of the notification
  - `type`: Type of notification (e.g., success, error, info)
  - `time`: Duration the notification should stay visible (in milliseconds)
  - `playSound`: Different sound play when launch notification

- **Ease of Use:**  
  An intuitive system that doesn't require hours of learning. Install and customize it quickly for seamless integration.

- **Versatile:**  
  Whether you're managing an RP server, organizing events, or just need a simple way to keep your players informed, **Noxen Notify** adapts to any situation.

### 🚀 **Why Choose Noxen Notify?**
- **Time-Saving:** Quickly set up and adjust without hassle.
- **Convenient:** Easily manage notification displays without disrupting gameplay.
- **Compatible and Flexible:** Works as a standalone system, but can be adapted to fit your server's specific needs using the customizable event system.

Enhance communication on your server with **Noxen Notify** – because a well-placed message can make all the difference.

```lua

-- title = string
-- message = string
-- type = error, success, info, warning
-- time = number (5000)
-- playSound = boolean (false by default)
-- image = string (Link img)


--CLIENT Exemple : 

TriggerEvent("noxen:notify", title, message, type, time, playSound, image)

--SERVER Exemple : 

TriggerClientEvent("noxen:notify",source, title, message, type, time, playSound, image)

```

---

Learn more and start using **Noxen Notify** today!
