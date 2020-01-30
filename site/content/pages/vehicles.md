---
url: /vehicles
title: Vehicles
date: 2020-01-27T04:19:13.502Z
description: The AUVic Fleet
---



# Polaris
![Polaris ](/img/uploads/AUVIC-2018-Final-Assembly-REV52.jpg)


Polaris is an open-framed AUV, designed with a low vehicle aspect ratio to facilitate station-keeping.
Polaris is equipped with 8 thrusters for 6 DOF control and has a large self-righting moment,
achieved through the positioning of a 960 cubic inch, watertight electronics housing at the top of the AUV.
Polaris’ subsystems are mounted to a plastic plate, produced using 2-axis manufacturing techniques.
The ease of manufacturing of this plate makes Polaris a modular framework, as subsystems can be added 
and removed without significant modifications to the vehicle.

<h4>Key Stats</h4>
	
<p>Dry Weight: 90 lbs<br>
									Overall Dimensions (excluding thrusters): 35 in L x 16.5 in W x 21.5 in H<br>
									Depth Rating: 300 ft (torpedo actuator)
								</p>




![Polaris ](/img/uploads/ezgif.com-crop.gif)




<h5>Custom Designed Thrusters: </h5>
									<p>
									AUVIC has developed custom thrusters which consist of three main components: the shroud, the motors, 
									and the propellers. Brushless DC motors were chosen due to their compatibility with freshwater. 
									These are used in conjunction with modified carbon fiber quadcopter propellers, 
									chosen due to their moderate pitch angle, motor-compatible mounting features, 
									and thickness near the base which is desirable for producing thrust. 
									The thruster shrouds contain a conical feature to direct fluid flow and are 3D printed using PLA, 
									with a high infill and coated with 3D Print Coating. </p>
									<div class="box alt">
										<div class="row uniform 50%">



![Motor](/img/uploads/motor_300px.png)


<h5>
									Golf Ball Dropper: </h5>
									<p>
									To drop golf balls on a target, Polaris is equipped with a golf ball dropper. 
									Golf balls are loaded and stored in a compartment on the AUV. To release these golf balls, 
									a stepper motor rotates inside a watertight housing. This stepper is magnetically coupled with the 
									golf ball dropping mechanism, allowing the golf ball to fall and hit the target.
									</p>


![BallDropper](/img/uploads/BallDropper1.jpg)



Torpedoes: <br>
									Polaris is equipped with two 3D printed torpedoes. These torpedoes are propelled using compressed air 
									stored inside a PVC cylinder and are actuated using a solenoid-controlled one-way valve. 
									<br>


![Torpedoes](/img/uploads/IMG-3933.jpg)



<h4>ELEC Highlights</h4>
									Motor Controller: <br>
									The motor controller was revised for 2018. In 2017, each motor controller could control up to 
									three motors on one PCB. In order to control all six motors on Nautilus’, two motor controllers were needed.  
									Early in the design process, AUVIC determined that Polaris was going to have eight motors to simplify 
									the control algorithm. AUVIC also wanted to integrate all the electronic speed controllers (ESCs) into one housing. The motor controller was upgraded in order to control eight motors simultaneously, while also using the PCB as a busbar. 
									Connectors on the motor control board were made reversible, to prevent damage to the motors if the 
									connector were connected in reverse. The system was upgraded from a F0 micro to a F4, 
									which has a floating point unit for PID controls and may be implemented in the future.
									<br>


![Elec_Board](/img/uploads/mc.png)

<br>
									Power Board: <br>
									The Power Regulation Board is a new PCB that is entering its manufacturing stage. The PCB will be the 
									central power hub for all components on the submarine. The board selects either the batteries or a tethered 
									power source to power the sub, and is capable of cutting power via an onboard microcontroller to various 
									systems in the submarine. RoboSub Rules requires that the sub have a “kill switch”, with can be pulled by 
									divers to cut power to the submarine. This is implemented by using a magnetic switch, which cuts power to 
									the sub when the switch is pulled. The Power Regulation Board must also be able to handle enough current 
									to power the eight motors. This board also acts as a monitor for the main housing of the submarine by 
									monitoring the housings’ pressure, temperature and humidity. It comes with an onboard water sensor, 
									and it has the capabilities to measure the external water pressure. It measures the current being 
									drawn from both the batteries and by individual subsystems, and has the ability to connect and disconnect 
									the batteries in parallel using control logic from the microcontroller. The board is fused to protect against 
									shortcircuits in any of the subsystems.
									<br>








![Power_Board](/img/uploads/power_board.png)

<br>
									The board has a USB connector that can be used for USART communications. 
									The microcontroller also has the capabilities to be powered either through USB or by the batteries, 
									which is useful for debugging purposes, when batteries aren't available. The relays are used to 
									switch between battery power and tether power, and will always chose tether power over battery power 
									when the tether is available. This can be used to easily conserve battery life during testing.
									<br>
									<br>
									Hydrophone Board: <br>
									Sonar systems are an integral part of the submarine’s design. To complete many of the objectives 
									in the competitions, the submarine must be able to locate pingers, or underwater speakers, 
									emitting sound at fixed frequencies. The solve this problem, our submarine has an array of 
									four hydrophones (underwater microphones). These hydrophones are all separated by a fixed/known 
									distance. By analyzing the phase difference of the incoming waves to the array of hydrophones, 
									we can triangulate the location of the pinger. To accomplish this, the hydrophone boards process 
									and convert the incoming data.The hydrophone boards consist of two sub-boards: the microcontroller
									board and the pre-amplification board. The pre-amplification board is placed at the same location 
									as the hydrophones, in a small housing at the bottom of the submarine. The board amplifies all incoming 
									signals from the hydrophones, and transmits them off to the main housing. In the main housing, the 
									microcontroller board converts the analog signals to digital, and sends the digital data to the main 
									computer.
									<br>




![HydroPhone_Micro](/img/uploads/hydrophone_micro.png)


<h4>Side Projects</h4>
									Acoustic Underwater Pinger<br>
									
									Ni-Cd Battery Charger<br>









<br/><br/><br/><br/><br/><br/><br/><br/><br/>


<h2><u> Legacy Builds </u></h2>


# Red Herring

![Red Herring](/img/uploads/red_herring4-620x304.png)


## Aerius (Retired)

![Aerius (Retired)](/img/uploads/aerius_1-300x225.jpg)
















