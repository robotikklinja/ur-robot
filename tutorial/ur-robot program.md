```
### **Robot Program**
- plastic:=0
- metal:=0
  - **Loop**
  
   - **MoveJ**
   - Start Pos
   - Wait PhotoSens_02=HI
   - Wait: 1.0
   - Ready_to_Pickup
   
   - **if InductSens_01=True**
   
    - **if metal=0**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - Metal_0_Pos
     - **MoveL**
      - Down_W_metal_0
      - Gripper Open (1)
      - Metal=1
      - Up_From_metal_0
      
    - **Elseif metal=1**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - Metal_1_Pos
     - **MoveL**
      - Down_W_metal_1
      - Gripper Open (1)
      - Metal=2
      - Up_From_metal_1
      
    - **Elseif metal=2**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - Metal_2_Pos
     - **MoveL**
      - Down_W_metal_2
      - Gripper Open (1)
      - Metal=3
      - Up_From_metal_2  
      
    - **Elseif metal=3**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - Metal_3_Pos
     - **MoveL**
      - Down_W_metal_3
      - Gripper Open (1)
      - Metal=4
      - Up_From_metal_3
      
    - **Elseif metal=4**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - Metal_4_Pos
     - **MoveL**
      - Down_W_metal_4
      - Gripper Open (1)
      - Metal=0
      - Up_From_metal_4
      
   - **Else**
    - **if plastic=0**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_0_pos
     - **MoveL**
      - Down_W_plastic_0
      - Gripper Open (1)
      - plastic=1
      - Up_From_plastic_0
      
    - **Elseif plastic=1**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_1_pos
     - **MoveL**
      - Down_W_plastic_1
      - Gripper Open (1)
      - plastic=2
      - Up_From_plastic_1
      
    - **Elseif plastic=2**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_2_pos
     - **MoveL**
      - Down_W_plastic_2
      - Gripper Open (1)
      - plastic=3
      - Up_From_plastic_2
      
    - **Elseif plastic=3**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_3_pos
     - **MoveL**
      - Down_W_plastic_3
      - Gripper Open (1)
      - plastic=4
      - Up_From_plastic_3
      
    - **Elseif plastic=4**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_4_pos
     - **MoveL**
      - Down_W_plastic_4
      - Gripper Open (1)
      - plastic=5
      - Up_From_plastic_4
      
    - **Elseif plastic=5**
     - **MoveL**
      - Down_to_Payload
      - Gripper Close (1)
      - Up_W_Payload
     - **moveJ**
      - plastic_5_pos
     - **MoveL**
      - Down_W_plastic_5
      - Gripper Open (1)
      - plastic=6
      - Up_From_plastic_5
```
