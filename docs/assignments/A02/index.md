# A2 – Truss Stress Analysis

# objectives:

-Design a light weight planar truss using A500 Steel

-FBD for joints and pins

-calculate cross-sectional area of truss elements 

-determine pin sizes based on shear forces

-estimate the total weight of the truss and pins

-create a CAD model 

-Compare CAD weight prediction with hand calculations

-Document key lessons learned from process. 


<img width="766" height="371" alt="image" src="https://github.com/user-attachments/assets/4b2426ce-9d10-474a-8dcb-52aff55d0464" />
### Values Given
P=20kN

a=.4m

b=.3m

Point A= Pin

Point B = Roller

# Design the truss structure using parameters
Before beginning the design of the truss, I first needed figure out how many members I needed. At first I didn't do this, so I struggled to know how many members I needed. In order to make a truss statically determinate I used the equation: 2j=M+3, Where j= joints and M=members. There are 4 joints which are points A,B,C and D. In order to make the equation true, there has to he 5 members. I played around with the members until I landed on the design below. My 5 members were BA, BC, CD, DA and CA.

<img width="675" height="322" alt="Screenshot 2026-09-02 141859" src="https://github.com/user-attachments/assets/538d911b-41ad-47ca-8580-497b7cf7109f" />

Plugging in all the given values, my sketch was complete and now I just need to find the forces. 
<img width="537" height="235" alt="Screenshot 2026-09-02 141913" src="https://github.com/user-attachments/assets/aaf38403-f11e-44b6-b542-8af3e2908569" />

I began with a FBD for external forces to solve for Ay and By. 
<img width="537" height="307" alt="Screenshot 2026-09-02 141920" src="https://github.com/user-attachments/assets/ba9e1770-5213-4a2b-9e19-9bdd18248713" />

Solving for Ay and By, I get 6.67 kN(c) and 6.67 kN(T).
<img width="843" height="386" alt="Screenshot 2026-09-02 141934" src="https://github.com/user-attachments/assets/a4a7e373-e7a7-48fc-9990-ffad0572f0b8" />
Once I had my external forces, I began with the internal forces. I chose to start at joint B because I already knew By, and I could easily solve for BC.
<img width="852" height="465" alt="Screenshot 2026-09-02 141949" src="https://github.com/user-attachments/assets/944f4726-f8cd-42e8-904d-c81ac8ce0a92" />
In order to solve for the members that were at an angle I had to use the ratio listed below. 
<img width="602" height="235" alt="Screenshot 2026-09-02 141954" src="https://github.com/user-attachments/assets/cf7bf069-f8d9-4a1e-a7b2-4de068307e81" />

I repeated this process again with joint C. At first when I was solving for CA, I used the same ratio as before. After finishing with joint C, I realized that the angles are different. I then went back and calculated the new sin and cos ratios. I marked these angles with phi and the previous ones with theta.
<img width="691" height="810" alt="Screenshot 2026-09-02 142037" src="https://github.com/user-attachments/assets/f214e67c-d7ac-46b3-82d2-3b3d2955d86c" />

Followed by joint D.
<img width="672" height="402" alt="Screenshot 2026-09-02 142047" src="https://github.com/user-attachments/assets/fd858fe4-8f0c-47e0-ac72-9a5fe367e419" />
I now had all force member values
<img width="323" height="192" alt="Screenshot 2026-09-02 142051" src="https://github.com/user-attachments/assets/372cf5ad-a416-4292-b771-9abf253137ee" />

# Calculate cross sectional area
<img width="642" height="461" alt="Screenshot 2026-09-02 142107" src="https://github.com/user-attachments/assets/b947986f-5dbb-404a-a693-f368d03a6f55" />

<img width="700" height="565" alt="image" src="https://github.com/user-attachments/assets/b5e7bd8a-2f2a-466d-b322-952f1e993c62" />

# Calculating cross sectional are of the pins
<img width="580" height="372" alt="Screenshot 2026-09-02 142121" src="https://github.com/user-attachments/assets/12c79fac-be53-4980-87bc-6efcef8abe6b" />

<img width="495" height="480" alt="Screenshot 2026-09-02 142128" src="https://github.com/user-attachments/assets/b770cd67-d95a-436b-a937-1b898ee8ee3c" />

# Generating 3D model of the truss

# Lessons learned

