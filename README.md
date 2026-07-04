<h1>Kelvin John Samson<br>
Project Portfolio</h1>
<h2>1.Transonic Stall Simulation</h2> 
-Ran a 2D simulation of the NACA 64a010 airfoil at an aoa of 15deg and a Mach number of 0.9 <br>
-Used the IDDES Turbulence model with AUSM flux scheme and the density based implicit solver in ANSYS Fluent <br>
-Post processed using ANSYS FLUENT, chord of the airfoil needed to be reduced to 1mm to be able to acheive a close to 1 y+ and CFL number (used 10)<br>
-This ideally has to be done in 3D as Turbuilence is 3D but the copmutational cost would be exorbidant in that case<br>
<p align='center'>
<img width="640" height="360" alt="Total Pressure buffet" src="https://github.com/user-attachments/assets/a32f49c3-26ee-48ef-b97d-926c18e07875" />
<img width="640" height="360" alt="Yplus" src="https://github.com/user-attachments/assets/aece3ccf-b76e-4f52-8840-ac3e5bca1144" />
</p>
-The total pressure plot reveals an interesting phenomenon of the pressure wave propogaiton due to the seperation<br>
-The Y+ plot on the surface of the airfoil reveals the Y+ at leading edge at around 1.6 and at the seperation point significantly lower than 1<br>

https://github.com/user-attachments/assets/a69cc938-941a-4139-8655-197fe18f086c

-Total Pressure Animation

https://github.com/user-attachments/assets/beaab731-9df7-49f2-a51a-b05e3e7c67c9

-Turbulence Intensity Animation

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <video src="https://github.com/user-attachments/assets/a69cc938-941a-4139-8655-197fe18f086c" controls="controls" style="width:100%;"></video>
      <p><b>First Video Demo</b></p>
    </td>
    <td width="50%" align="center">
      <video src="https://github.com/user-attachments/assets/beaab731-9df7-49f2-a51a-b05e3e7c67c9" controls="controls" style="width:100%;"></video>
      <p><b>Second Video Demo</b></p>
    </td>
  </tr>
</table>
