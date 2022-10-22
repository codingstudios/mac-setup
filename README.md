# Mac Setup
The setup process of [@joeleeofficial](https://joe.js.org) mac

- Create a user without admin privileges
- Enable file vault
- Enable firewall
- Enable low power mode for both on battery / plugged into power
- Disable prevent going sleep when display off
- Enable screen time
- Sign in Apple ID on the user account
- Security & Privacy: <br><img width="326" alt="image" src="https://user-images.githubusercontent.com/81070048/195988695-910d2a77-227d-40f1-8f88-16aaf1dea0a1.png"><br><img width="326" alt="image" src="https://user-images.githubusercontent.com/81070048/195988772-0a0dc6ce-0f34-4030-a82d-c09f1ed519b6.png">
- Turn off Sharing: <br><img width="326" alt="image" src="https://user-images.githubusercontent.com/81070048/195989048-6dc32428-b8e0-43d7-86d3-945c6dcb0e79.png">
- Privacy > Disable all analytics
- Change siri settings: <br><img width="326" alt="image" src="https://user-images.githubusercontent.com/81070048/195988959-b07bed92-341f-4b09-8be4-a02952b00d6b.png">
- Enable find my mac
- Settings > General: <br><img width="289" alt="image" src="https://user-images.githubusercontent.com/81070048/195978887-a2205a31-e4d6-4153-9589-2f330e4e1c12.png">
- Dock & Menu Bar: <br><img width="231" alt="image" src="https://user-images.githubusercontent.com/81070048/195978683-890b1867-bb1d-4054-9c72-d6b147ed0d35.png">
- Trackpad > Enable all trackpad gesture, scroll & zoom, point & click
- Trackpad > Click - Medium
- Trackpad > Tracking speed fastest
- Trackpad > enable Silent Clicking & force click and haptic feedback
- Keyboard: <br><img width="329" alt="image" src="https://user-images.githubusercontent.com/81070048/195978490-42e4aff0-84bc-4e99-a802-9a3c4125645c.png">
- Create these shortcuts:
    - Greyscale: <br><img width="532" alt="image" src="https://user-images.githubusercontent.com/81070048/195978548-39e11354-7b73-4bc3-8713-5b0e00fcfaa7.png">
   - Text Capture:  <br><img width="532" alt="image" src="https://user-images.githubusercontent.com/81070048/195978565-de7344a6-b9d0-4335-b733-1eb5198179ac.png">
- Run `defaults write -g ApplePressAndHoldEnabled -bool false` in terminal to disable press and hold an alphabet for options
- Uninstall unused apps like Garage Band, Keynote, Numbers, .etc
- Install mozilla firefox
    - Settings General
      > <img width="291" alt="image" src="https://user-images.githubusercontent.com/81070048/195989450-e6519587-156c-4598-96db-a0e41bdfb8cf.png"><br><img width="291" alt="image" src="https://user-images.githubusercontent.com/81070048/195989483-f3fa88a6-84a5-4188-ae1f-4010bc7aecea.png"><br><img width="291" alt="image" src="https://user-images.githubusercontent.com/81070048/195989507-e0d9c88d-38a8-4fff-beee-97fca0972639.png"><br><img width="291" alt="image" src="https://user-images.githubusercontent.com/81070048/195989534-eb74fc0e-0cbd-4e09-890d-4afda52d1331.png"><br><img width="291" alt="image" src="https://user-images.githubusercontent.com/81070048/195989567-cc192d4e-dfb4-435d-b80a-389cbe053a23.png">
    - Settings Home
      > <img width="273" alt="image" src="https://user-images.githubusercontent.com/81070048/195989619-15632fe6-8783-4733-9d68-a169aeb98b09.png">
    - Settings Search
      > <img width="367" alt="image" src="https://user-images.githubusercontent.com/81070048/195989659-c919cc35-de28-445a-a3fb-de2624062c80.png">
    - Settings Privacy & Security
      > Strict Mode
      > Do not track: Always
      > Uncheck everything in Login & Passwords
      > Never Remember History
      > Uncheck everything in Address Bar
      > Disable everything in Firefox Data Collection And Use
      > HTTPS only mode in all windows
    - Never show bookmark toolbar
    - Delete default bookmarks
    - Install uBlock Origin & Prevent Misclick (login required)
    - Setup uBlock Origin
      > <img width="294" alt="image" src="https://user-images.githubusercontent.com/81070048/195989979-8f4cac66-1c67-4907-b09e-9868ad6e1efc.png"><br>
      > Set Rule: <br>
      ```
        no-csp-reports: * true
        no-large-media: * true
        no-large-media: behind-the-scene false
        no-popups: discord.com true
        no-remote-fonts: * true
        no-remote-fonts: classroom.google.com false
        no-remote-fonts: developers.google.com false
        no-scripting: * true
        no-scripting: discord.com false
        no-scripting: github.com false
        no-scripting: accounts.google.com false
        no-scripting: classroom.google.com false
        no-scripting: developers.google.com false
        no-scripting: docs.google.com false
        no-scripting: drive.google.com false
        no-scripting: mail.google.com false
        no-scripting: www.google.com false
        no-scripting: www.youtube.com false
        behind-the-scene * * noop
        behind-the-scene * 1p-script noop
        behind-the-scene * 3p noop
        behind-the-scene * 3p-frame noop
        behind-the-scene * 3p-script noop
        behind-the-scene * image noop
        behind-the-scene * inline-script noop
      ```
    
    
 > This is the setup process of [Chee Yong Lee](https://github.com/leecheeyong]'s Mac, feel free to use the list above as a reference. 
   Give [@joeleeofficial](https://github.com/joeleeofficial) & [@leecheeyong](https://github.com/leecheeyong) a follow if you found this useful.






    
