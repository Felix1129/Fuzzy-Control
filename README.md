# Fuzzy-Control
This thesis studied the networked control systems (NCSs) of polynomial fuzzy time-delay systems based on piecewise polynomial Lyapunov functions (PPLF), and applied 
them to the path tracking control of mobile robots and quadrotors. The number of fuzzy rules could be reduced to two by using the novel modeling method, which greatly reduces the 
hardware cost. Both mobile robots and quadrotors had the problem of time delay in the plant. The time delay system developed in this work could tolerate the time delay of the plant 
through the modeling method of calculating the time delay of the plant additionally. The Lyapunov-Krasovskii piecewise polynomial functional function was designed using the 
minimum-type polynomial Lyapunov piecewise function. By reducing the stable condition number, the gain solution space could be expanded, and then the performance of the controller 
was better than the existing polynomial fuzzy network. Since the number of stable conditions was less than the existing methods, the proposed method could also expand the feasible 
solution space and obtain better controller performance compared with the general Lyapunov function controller. Thus, based on the piecewise polynomial Lyapunov-Krasovskii 
function, considering the time delay and package dropoutcaused by the network, a robust stability condition is proposed in this work with calculated time delay in the SOS-based 
relaxation stabilization condition, and an SOS-based formation relaxation condition. The theorems proposed in this work consider the network-caused package dropout and time delay. 
Theorem 1 additionally considers the time delay of the plant and then simulates the virtual model of the mobile robot and the quadrotor to verify that the proposed theorem can be applied to 
the controller resisting external disturbances, it tolerates model uncertainty and formation effectiveness. Finally, the designed network controller was used for the path tracking of the mobile 
robot and the quadrotor, and the performance of the theorem proposed in this work was verified to be better than the existing controller.
