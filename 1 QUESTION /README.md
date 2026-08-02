Aim


The aim of this experiment is to simulate Smart City Internet of Things (IoT) traffic using MATLAB and analyze the impact of varying the number of sensor nodes on network performance. The performance is evaluated using End-to-End Delay, Packet Delivery Ratio (PDR), Bandwidth Utilization, and Throughput. The objective is to understand how increasing the number of IoT devices affects communication efficiency and overall network performance.

Introduction


The Internet of Things (IoT) is one of the most significant technologies used in smart city applications. It enables physical devices such as sensors, cameras, traffic lights, parking systems, streetlights, and environmental monitoring devices to communicate over the Internet. Smart cities rely on thousands of interconnected sensors to collect real-time information and improve public services.
IoT devices continuously generate data and send it to gateways, which forward the information to cloud servers for processing. The cloud analyzes the collected data and provides useful insights to city administrators. As the number of sensors increases, the amount of generated traffic also increases. This may improve monitoring capabilities but can also lead to network congestion, increased delay, reduced packet delivery, and higher bandwidth usage.
Simulation is an effective method for studying the behavior of IoT networks without deploying physical devices. MATLAB provides an efficient environment for generating network traffic, calculating performance metrics, and visualizing results using graphs.


Output

<img width="745" height="502" alt="Screenshot 2026-08-02 181103" src="https://github.com/user-attachments/assets/fb8cec2d-f4d3-466b-a3d9-863afae10b24" />
<img width="730" height="512" alt="Screenshot 2026-08-02 181043" src="https://github.com/user-attachments/assets/588451bf-ed20-4f5d-a0e6-bd46124f08bd" />
<img width="728" height="500" alt="Screenshot 2026-08-02 181027" src="https://github.com/user-attachments/assets/c3905af9-fdbe-425c-8681-3973017a4924" />
<img width="711" height="475" alt="Screenshot 2026-08-02 181002" src="https://github.com/user-attachments/assets/f7fe5db0-ff80-40ea-a80d-4f4716fdfe73" />


Conclusion


The MATLAB simulation demonstrates that the performance of a Smart City IoT network is significantly affected by the number of sensor nodes. As the sensor count increases, network traffic becomes heavier, resulting in increased end-to-end delay and bandwidth utilization. Packet Delivery Ratio decreases slightly due to congestion and packet loss, while throughput increases because more data is transmitted. These results show that careful planning of sensor deployment, routing strategies, and bandwidth allocation is essential for building an efficient and reliable Smart City IoT network. MATLAB proves to be an effective tool for analyzing network behavior before real-world implementation.


