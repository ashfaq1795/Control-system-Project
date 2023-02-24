This is my semester project of control system subject 7th semester in universtiy of engineering and technology, Peshawar. 
In this project given tasks were to perform.

-----------------------------------------------------------------------------------------------------
a. Consider the state-space of Problem 22, Page 148 of Norman Nise Book Edition
5.
b. Check the stability of the system using all methods that you know.
c. Compute the controllabililty and observerability for the system. If the system is
unstable design a suitable controller for it.
d. Simulate the system using the controller that you design and show all the
responses.
e. Design a PID controller and show the response of the system using PID Controller. Compare the results obtained in parts d and c.
f. Compute the steady state error before and after designing controller.
g. Design a tracking controller for step tracking of amplitude 5u(t) and ramp
tracking of 5ut(t).
-----------------------------------------------------------------------------------------------------

First of all I checked the stability of the system using 5 different techniques (stability_checking.m).
Then I checked controllability and observerability test (controllability_observerability_test.m).
As the system is stable so I didn't design any controller and showed all responeses without using any controller.
Then I designed PID controller for 4 test signals separatly (step, impulse, ramp, Parabolla) and showed the responses.
After that I calculated the steady-state error for each singal. steady state error is the difference between the final value of system response and original signal.
Finally I designed the tracking controller for 5u(t) and 5ut(t). Tracking controller is a controller used for matching system response and input signal.

# Control-system-Project
