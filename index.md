<table border="0">
  <tr>
    <td width="35%">
      <img src="/DSC_251.jpg" width="100%">
    </td>
    <td width="65%">
      
      <p>My name is Guanqun Mu (穆冠群). </p>
      <p> I am studying for a B.Sc. degree at Physic Department, Wuhan University.</p>
      <p>I am interested in quantum information science and technology. especially <b>ion trap model</b>(Experiement) and realization and simulation of <b>quantum error correction algorithm</b></p>
    </td>
  </tr>
</table>


## **Research Experience**


### **Designing Control System for Ion Traps & Realizing Zeeman Scan and Rabi Scan of a Single Qubit**
>Mang Feng's Ion Trap Group, Wuhan Institute of Physics and Mathematics (WIPM) ,Chinese Academy of Sciences (CAS)  
March, 2019 -- Now

  Artiq is adopted by ion trap groups from NIST and Oxford University as the control system of ion traps. It integrates FPGA, AOM and DDS, and can control experimental processes through Python. Our group also adopted it for the operation of quantum information.
  
  As the main developer of Artiq in our group, I designed functions that can implement zeeman scan and rabi scan for a single qubit and paluse shaping for DDS to Reduce AC-Stark effect. In addition, Based on scalability of Python, I made a custom GUI to facilitate the experimental process.

<table border="0">
  <tr>
    <td width="40%">
      <img src="/How_does _CS_work.png" width="100%">
      
    </td>
    <td width="60%">
      <img src="/Dashboaed.png" width="100%">
      
    </td>
  </tr>
</table>

The left figure shows the structure of control system for ion traps based Artiq. The right figure shows The dashboard and customized GUI. 

For more detalls, click here to see the github page of our contorl system :[https://github.com/GuanQunMu/IonTrap-WIPM](https://github.com/GuanQunMu/IonTrap-WIPM)

___

 
 
 
### **Time Tagging of Photons from Ion Traps**  
>Manas Mukherjee's Ion Trap Group, CQT, National University of Singapore (NUS)  
 June, 2019 -- September, 2019

With FPGA Programing (Verilog) and Python, I designed a system that can tag the time of photons emitted from ion traps. On the PC side, the GUI is made by Python, and the communication between the PC and FPGA uses the JTAG protocol ,which is realized by Python. On the FPGA side, through Verilog and Quartus, I implemented FPGA programming to collect and store the data of the emission time of each photon emitted from ion traps.

<table border="0">
  <tr>
    <td width="100%">
      <img src="/TimeTagging.png" width="75%">
      
    </td>
  </tr>
</table>

This figure shows What happens in FPGA: From the binary bit string transmitted by the JTAG protocol on the far left, the data passes through the translator to determine when to end the experiment. In the meanwhile, the signal from the PLL passes through the counter to determine the current time, waiting for the signal in the PMT to trigger.

___


### **Simulation of the Surface Code and Toric Code**  
>Yongjian Han's Theory Group, University of Science and Technology of China (USTC)  
July, 2018 -- January, 2019

The surface code and toric code are one of the most popular quantum error correction codes. (Widely used in superconducting quantum computing).

I designed a program in javascript to simulate the operation of the surface code and toric code, explored their thresholds under specific conditions, and verified their properties: The fidelity of logic gates will increase as the size of the qubits increases when its logical error rate is below the threshold.

<table border="0">
  <tr>
    <td width="50%">
      <img src="/Face.png" width="100%">(a)
       
      
    </td>
    <td width="50%">
      <img src="/TORIC.png" width="100%">(b)
      
    </td>
  </tr>
</table>

(a) A two-dimensional array implementation of the surface code. (b) The fidelity of one logical qubit array. The x-axis represents the error rate of the logic gate, and the y represents the number of errors in 10,000 Monte Carlo samples. Different colors represent different array sizes. It can be found that the threshold is 0.1050.

For more detalls, You can go to my Github page to use my surface code program: [https://github.com/GuanQunMu/Surface-Code](https://github.com/GuanQunMu/Surface-Code)


## Skills
20 k+ lines Python & Javascript Codes  
1 year FPGA Programing Experience (Verilog)  
1 year Matlab & Mathematica Experience  
2 year Physical Simulation Experience  

## Contact

If you have any question, be free to contact me: **guanqun_mu@whu.edu.cn**
