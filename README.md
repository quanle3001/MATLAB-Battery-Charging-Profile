# Team 2's Solution to MATLAB and Simulink Challenge Project 5: Modeling and Analyzing a Battery Charging Profile

[Program link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub)

[Project description link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/Classroom%20Challenge%20Projects/Projects/Modeling%20and%20Analyzing%20a%20Battery%20Charging%20Profile)

# Project details

Lithium-Ion battery charging involves non-linear changes in current and voltage over time, leading to difficulties in predicting the battery's charge time and energy efficiency. This project uses a simple RC equation to model a battery's charging profile and analyze it charging time, energy delivered, and resistive energy loss. The analysis of a battery's charging profile is important because it allows engineers to identify areas for improvement by reducing resistive energy loss and mitigating other factors that affect battery efficiency.

# How to run section

To run the battery charging profile model, the MATLAB Curve Fitting Toolbox is necessary. After installing the toolbox, open the MATLAB Live Script file and click the Run button.

# How to reproduce results

Step 1: Open 'BatteryCharging_StudentProjectTemplate.mlx' in MATLAB.

Step 2: Install the Curve Fitting Toolbox if it is not already installed.

Step 3: Run the entire Live Script from Task 1 through Task 3.

Step 4: The script will load the battery dataset, analyze the selected cycle, fit the RC equation, and generate graphs and calculations for each task.

Note: For task 3 and testing a different charging cycle, adjust the charging-time mask and analysis intervals:

chargeTimeMask = time >= 0 & time <= 1850;
interval1 = chargeTime >= 50 & chargeTime <= 250;
interval2 = chargeTime >= 350 & chargeTime <= 550;
interval3 = chargeTime >= 650 & chargeTime <= 1200;
interval4 = chargeTime >= 1300 & chargeTime <= 1800;

The interval boundaries should be selected based on the charging transitions visible in the voltage, current, and power plots. For the cycle analyzed in this project, approximately 50-100 seconds near transitions were excluded to reduce the effect of noise and abrupt changes.

# Demo/Results
<img width="525" height="351" alt="Screenshot 2026-08-06 at 9 23 25 PM" src="https://github.com/user-attachments/assets/9d7759f4-c7e7-4ddf-ac6a-cfbdb7385e6e" />
<img width="622" height="242" alt="Screenshot 2026-08-06 at 9 24 47 PM" src="https://github.com/user-attachments/assets/75f39af1-9c32-4cd2-9a12-10d6b5945ab5" />
<img width="622" height="242" alt="Screenshot 2026-08-06 at 9 25 17 PM" src="https://github.com/user-attachments/assets/996caac5-c03a-4d1b-9c34-cedcb1432d7b" />
<img width="622" height="242" alt="Screenshot 2026-08-06 at 9 25 38 PM" src="https://github.com/user-attachments/assets/c2225087-758d-42e8-9286-6fc6dc1599a4" />
<img width="429" height="178" alt="Screenshot 2026-08-06 at 9 28 34 PM" src="https://github.com/user-attachments/assets/ef9a9d31-5ae7-429f-8158-3dcae6a1161c" />
<img src="images/task3-summary-table.png" width="429" height = "178">

See attached pdf of "BatteryCharging_StudentProjectTemplate" in the GitHub repository.
  
# Reference(s)
[MATLAB Project Description and Template](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/Classroom%20Challenge%20Projects/Projects/Modeling%20and%20Analyzing%20a%20Battery%20Charging%20Profile)
