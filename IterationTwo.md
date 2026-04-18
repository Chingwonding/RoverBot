# Iteration 2: Wireless Control & Logic
This iteration focused on cutting the cord. By switching to the ESP32, I added WiFi capabilities for remote control and integrated a battery pack for full mobility. As you can see even with the bang bang and all my efforts to try and keep the robot straight, it ultimately failed (for now). 

---

<div style="background-color: #f6f8fa; border-radius: 12px; padding: 30px; border: 1px solid #d0d7de;">
  <h3 style="margin-top: 0; text-align: center;">Testing & Encoders</h3>
  
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <video src="https://github.com/user-attachments/assets/1d4e8dc8-860e-4acf-920f-80815419134d" width="380" controls style="border-radius: 10px; border: 2px solid #24292f;"></video>
    <video src = "https://github.com/user-attachments/assets/c2274cb7-3a77-46e4-b5eb-f941544e2488" width="380" controls style="border-radius: 10px; border: 2px solid #24292f;"></video>

  </div>
  
  <p style="text-align: center; color: #57606a; font-size: 0.9em; margin-top: 15px;">
    <em>Testing the remote ESP32 connection and the encoder-based bang-bang controller.</em>
  </p>
</div>

---

### Hardware Upgrades
* **ESP32 Integration:** Enabled WiFi capabilities, allowing for remote steering and commands.
* **Onboard Power:** Added a battery pack (that I usually use to charge my phone), removing the physical tether to a power source.
* **Encoders & Logic:** Implemented encoders to track distance. 
* **Bang-Bang Controller:** Created a crude controller to help the rover drive in a straighter line by compensating for motor variance using encoder tick feedback.
* **BreadBoard** Used breadboard because without it, everything got extremely messy.

### Challenges
As seen in the videos, the rover still struggled with traction and consistency, often getting tripped up on dirty surfaces like my floor. 

