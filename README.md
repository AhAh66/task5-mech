# task5-mech
# Forward Kinematics for a 2-Link Robot Arm
 based on the joint angles (𝜃₁ and 𝜃₂) and link lengths (𝐿₁ and 𝐿₂).
![‫مسار الهندسة الميكانيكة - 5 - YouTube - Google Chrome‬ 2_13_2025 5_14_12 PM](https://github.com/user-attachments/assets/93edde06-8ba8-47fd-a67a-9c43b11a6a70)

## Given Data:
- **𝐿₁ = 10 cm** (length of the first link)
- **𝐿₂ = 15 cm** (length of the second link)
- **𝜃₁ = 30 degrees** 
- **𝜃₂ = 45 degrees** 

## Forward Kinematics Equations:

The equations to calculate the final position of the end-effector are:

### 1. x Equation:
\[
x = L_1 \cdot \cos(\theta_1) + L_2 \cdot \cos(\theta_1 + \theta_2)
\]

### 2. y Equation:
\[
y = L_1 \cdot \sin(\theta_1) + L_2 \cdot \sin(\theta_1 + \theta_2)
\]

## Calculations:

- **𝐿₁ = 10 cm**
- **𝐿₂ = 15 cm**
- **𝜃₁ = 30 degrees**
- **𝜃₂ = 45 degrees**

### Steps:
1. Convert the angles from degrees to radians:
   \[
   \theta_1 = 30^\circ = \frac{30 \cdot \pi}{180} \approx 0.5236 \, \text{radians}
   \]
   \[
   \theta_2 = 45^\circ = \frac{45 \cdot \pi}{180} \approx 0.7854 \, \text{radians}
   \]

2. Calculate the x and y coordinates:
   \[
   x = 10 \cdot \cos(0.5236) + 15 \cdot \cos(0.5236 + 0.7854) \approx 12.54 \, \text{cm}
   \]
   \[
   y = 10 \cdot \sin(0.5236) + 15 \cdot \sin(0.5236 + 0.7854) \approx 19.49 \, \text{cm}
   \]

## Final Result:
The final position of the end-effector is:
- **𝑥 ≈ 12.54 cm**
- **𝑦 ≈ 19.49 cm**

## Conclusion:
Using the Forward Kinematics equations, we can determine the position of the robot arm's end-effector based on the given angles and link lengths. These equations are fundamental in robot motion control and design.


