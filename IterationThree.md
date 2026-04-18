Iteration 3

# Iteration 3: 3D Printed Chassis
This is the first CADDED and 3D-printed chassis iteration of the robot. In addition, the current design was my first CAD design, and I made a lot of goofy mistakes that prevented the robot from functioning as I had planned. Hardware wise, I added the IMU (which I learned how to solder the header pins for), the LCD display, and the Ultrasonic sensor. Despite spending 10+ hours designing the cad alone, I made stupid mistakes like forgetting that walls take up space, meaning lots of dimensions meant to fit snuggly just didn't. As seen in the photo, the L298 lies on top of the batteries, while originally the plan was for the L298 to be in the hole part with one battery on each side fastened using zipties. 

---


  <table border="0" cellpadding="0" cellspacing="0" align="center" style="border-collapse: collapse; width: 600px;">
  <tr>
    <td align="left" style="padding: 0; width: 300px;">
      <img src="https://github.com/user-attachments/assets/f1295c69-77f0-48bd-9216-2c0d7899ff5a" width="295" style="display: block; border-radius: 8px;">
    </td>
    <td align="right" style="padding: 0; width: 300px;">
      <img src="https://github.com/user-attachments/assets/aef44ac0-a7d1-4aca-84de-44ac8b195c70" width="295" style="display: block; border-radius: 8px;">
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding: 10px 0;">
      <img src="https://github.com/user-attachments/assets/20785284-1c47-498d-be87-b45052823ffb" width="600" style="display: block; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding: 10px 0;">
      <p style="color: #666; font-style: italic; margin-bottom: 10px;">CAD Design Iterations</p>
      <div style="display: flex; justify-content: center; gap: 5px;">
        <img src="https://github.com/user-attachments/assets/6e2d21e8-921a-49d4-9e0d-403d9b846d41" width="195" style="border-radius: 5px;">
        <img src="https://github.com/user-attachments/assets/74c32c57-2696-445c-8d15-6dde93f43b3c" width="195" style="border-radius: 5px;">
        <img src="https://github.com/user-attachments/assets/96994d5e-d81d-43c2-b18c-d5617ce501ac" width="195" style="border-radius: 5px;">
      </div>
    </td>
  </tr>
</table>

      


---

### Improvements in this Version
* **Novel Hardware Additions:** The green PLA provides a rigid base that prevents the motors from shifting.
* IMU: measured and calculated robot heading, plan to write code to replace encoder-based bang bang to imu based bang bang
* Ultrasonic Sensor: For calculating distance, will be used to avoid obstacles later
* **Skills:**
* Learned Onshape for CAD (somehow the motors fit perfectly with the chassis, but I forgot to account for walls in other parts)
* Learned Soldering (initially sucked...I think I understand it now, even with the parkinsons hand-shake)



