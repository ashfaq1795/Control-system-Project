# Control-system-Project
This is my semester project of control system subject 7th semester in university of engineering and technology, Peshawar. 
In this project given tasks were to perform.

_________________________________________________________________________________________________________________________________________
a. Consider the state-space of Problem 22, Page 148 of Norman Nise Book Edition.                                                                                         
b. Check the stability of the system using all methods that you know.  <br>
c. Compute the controllabililty and observerability for the system. If the system is unstable design a suitable controller for it. <br>
d. Simulate the system using the controller that you design and show all the responses.  <br> 
e. Design a PID controller and show the response of the system using PID Controller. Compare the results obtained in parts d and c.  <br>
f. Compute the steady state error before and after designing controller.   <br>
g. Design a tracking controller for step tracking of amplitude 5u(t) and ramp tracking of 5ut(t).  <br>
__________________________________________________________________________________________________________________________________________

The state space model of Problem 22 is, <br>
A=[-0.435 0.209 0.02; 0.268 -0.394 0; 0.227 0 -0.02]  <br>
B=[1;0;0]  <br>
C=[0.0003 0 0]  <br>
D=[0]   <br>

First of all I checked the stability of the system using 5 different techniques (stability_checking.m).
Then I checked controllability and observerability test (controllability_observerability_test.m).
As the system is stable so I didn't design any controller and showed all responses without using any controller.
Then I designed PID controller for 4 test signals separately (step, impulse, ramp, Parabola) and showed the responses.
After that I calculated the steady-state error for each signal. steady state error is the difference between the final value of system response and original signal.
Finally, I designed the tracking controller for 5u(t) and 5ut(t). Tracking controller is a controller used for matching system response and input signal.


