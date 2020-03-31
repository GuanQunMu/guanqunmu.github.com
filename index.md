<table border="0">
  <tr>
    <td width="35%">
      <img src="/DSC_252.jpg" width="100%">
    </td>
    <td width="65%">
      
      <p> My name is Guanqun Mu and currently I am an undergraduate student at Wuhan University, Hubei, P R China. My major subject is physics and expected to graduate in summer 2020. </p>
      <p>I am keenly interested to peruse my Masters and Doctorate in scalable quantum computing systems. My interest currently meets in <b>quantum information process in ion traps</b> and <b>simulation of physical processes in quantum computing models</b>.</p>
      <p>Therefore, in regard to get excel in the after mentioned research filed I have tried my best to participated in different ion trap groups. A short detail is as given below. </p>
    </td>
  </tr>
</table>


## **Research Experience**


### **Designing the Control System for Rabi Scan and Zeeman Scan of qubits in Ion Traps**
>Mang Feng's Ion Trap Group, Wuhan Institute of Physics and Mathematics (WIPM) ,Chinese Academy of Sciences (CAS)  
March, 2019 -- Now

  Applied by a laser with the rabi frequency, a two-level ion will continuously oscillates between levels. Ones can control the quantum gate acting on a qubit by setting the rabi oscillation time, which is called the rabi scan. To achieve it, an control system is required. Artiq is adopted by ion trap groups from NIST and Oxford University as the control system of ion traps. It integrates FPGA, AOM and DDS, and can control experimental processes through Python. 
  
  In our group, as the main developer of the control system based on Artiq, I designed functions that can implement rabi scan and zeeman scan for qubits and paluse shaping for DDS to Reduce AC-Stark effect. In addition, to facilitate the experimental process, I made a custom GUI by Python.

<table border="0">
  <tr>
    <td width="30%">
      <img src="/rabi.png" width="100%">(a)
      <img src="/How_does _CS_work.png" width="100%">(b)
    </td>
    <td width="70%">
      <img src="/Dashboaed.png" width="100%">(c)
      
    </td>
  </tr>
</table>

(a) Interacting with the 729 nm wave length laser, the Ca + ion oscillate between the ground state and the D5/2 state. (b) Structure of our control system for ion traps based on artiq. (c) The dashboard and customized GUI shown on the PC. 

Click here to see the github page of our contorl system and use it: [https://github.com/GuanQunMu/IonTrap-WIPM](https://github.com/GuanQunMu/IonTrap-WIPM)

___

 
 
 
### **Time Tagging of Photons emitted from Ion Traps**  
>Manas Mukherjee's Ion Trap Group, CQT, National University of Singapore (NUS)  
 June, 2019 -- September, 2019

With FPGA Programing (Verilog) and Python, I designed a system that can tag the time of photons emitted from ion traps. On the PC side, I made the GUI by Python, and implement communication between the PC and the FPGA with the JTAG protocol ,which is realized by Python. On the FPGA side, through Verilog and Quartus, I designed programs to collect, analyse and store the data of TTL signals from PMT. By comparing signals from the PMT with signals of PLLs, the system can tag the time when the photons are emitted from the ion traps.

<table border="0">
  <tr>
    <td width="35%">
      <img src="/coherent.gif" width="100%">(a)
    </td>
    <td width="65%">
      <img src="/TimeTagging.png" width="100%">(b)
      
    </td>
  </tr>
</table>
(a) Figure from Wikipedia. Time evolution of the probability distribution with quantum phase of a coherent state with α=3. (b) The FPGA program: From the binary bit string transmitted by the JTAG protocol on the far left, the data passes through the translator to determine when to end the experiment. In the meanwhile, the signal from the PLL passes through the counter to determine the current time, waiting for the signal in the PMT to trigger.

___


### **Simulation of the Surface Code and Toric Code**  
>Yongjian Han's Theory Group, University of Science and Technology of China (USTC)  
July, 2018 -- January, 2019

As the number of entangling qubits increases, the fidelity of multi-qubit gates will decrease, which is one of the biggest obstacles to achieving scalable quantum computing. However, encoded by surface code, which is used by Google, the fidelity of quantum gates of  encoded qubits will increase as the size of physical qubits array increases.

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

(a) A two-dimensional array implementation of the surface code. (b) The fidelity of one logical qubit array. The x-axis represents the error rate of the logic gate, and the y represents the number of errors in 100,000 Monte Carlo samples. Different colors represent different array sizes. It can be found that the threshold is 0.1050.

Click here to see the Github page of this project and use my surface code program: [https://github.com/GuanQunMu/Surface-Code](https://github.com/GuanQunMu/Surface-Code)

___



## **GPA**
Overall GPA: **85 /100**  
Major GPA: **88 /100**  
Core Courses:  
Quantum Mechanics **(90)** / Advanced Quantum Mechanics **(88)** / Electrodynamics **(95)** / Theoretical Mechanics **(93)** / Thermodynamics and Statistical Mechanics **(85)** / Computational Physics **(91)** / Mechanics **(96)** / Atomic and Nuclear Physics **(98)** / Optics **(89)** / Electricity and Magnetism **(90)**

___

 
## **Skills**
20 k+ lines Python & Javascript Codes  
1 year FPGA Programing Experience (Verilog)  
1 year Matlab & Mathematica Experience  
2 year Simulation of Physical models Experience  

___

 

## **Contact**

E-mail: **guanqun_mu@whu.edu.cn**
