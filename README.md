### Forrest Lee Erickson 👋
**CAUTION Amused Scientist** (I am not mad yet. Thou I am angry about the world not living up to the potential science can offer.)

B.S. Physics, U of MN  
Hobbies in no particular order: 
* Amateur Astronomy 
* ESP32 
* Arduino and Artuino UNO
* KiCad
* FreeCAD
* RPi 
* Linux 
* Amateur Radio (KE4AXQ) 
* Wood & metal working
* Private Pilot 
* SCUBA
* Archeology
* Paleontology
* Freethought (fighting supernatural nonsense where ever found.)

Recently (2024-2025) I have been volunteering with Public Invention on the Krake Project. See: https://github.com/PubInv/krake  
Krake is the child project of GPAD project (2022). See:https://github.com/PubInv/general-alarm-device  
Public Invention is a non profit company whose mission is: 
> We invent things that help all people. We empower inventors, technologists, and students to publish, find, and collaborate on invention ideas through direct coaching, team formation, curation of work, publication, co-working/learning events, and in some cases material support.

 
Other:  
Facebook: https://www.facebook.com/forrest.erickson.5    
Youtube: https://www.youtube.com/@forresterickson6225  
Your ORCID iD: 0009-0006-3624-0382, Your ORCID record is https://orcid.org/0009-0006-3624-0382

### Super Power
Novel and diverse spelling

### Things I want to Learn
Tensor Notation.
<hr>  

#### The Transformation Chain
Example of two rotaions. Each CCW. First by 45 degrees and then an additional 30 degrees.

The original vector in the **Standard** system:

$$
V^j = \begin{pmatrix} 1 \\ 0 \end{pmatrix}
$$  

An alternate form of the original vector in the Standard system: $V^j = [1, 0]^\intercal$

The first transformation (45° CCW) to the **Primed** system: $V'^i = A^i{}_j V^j$

The second transformation (+30° CCW) to the **Double-Primed** system: $V''^k = B^k{}_i V'^i$

The **Total Transformation** from start to finish: $V''^k = (B^k{}_i A^i{}_j) V^j$


The first rotation matrix ($A^i{}_j$) for 45° CCW:

$$
A^i{}_j = \begin{bmatrix} 
\cos(45^\circ) & \sin(45^\circ) \\ 
-\sin(45^\circ) & \cos(45^\circ) 
\end{bmatrix} \approx \begin{bmatrix} 
0.707 & 0.707 \\ 
-0.707 & 0.707 
\end{bmatrix}
$$

The second rotation matrix ($B^k{}_i$) for an additional 30° CCW:

$$
B^k{}_i = \begin{bmatrix} 
\cos(30^\circ) & \sin(30^\circ) \\ 
-\sin(30^\circ) & \cos(30^\circ) 
\end{bmatrix} \approx \begin{bmatrix} 
0.866 & 0.500 \\ 
-0.500 & 0.866 
\end{bmatrix}
$$


<hr>


### Something for many programs
// Program information  
#define COMPANY_NAME "Amused Scientist"  
#define PROG_NAME "Explosive_Space_Modulator"  
#define VERSION "; Rev: 0.99"  //  
#define DEVICE_UNDER_TEST "Hardware: Illudium Q-36"  //A model number  
#define LICENSE "GNU Affero General Public License, version 3 "  
#define WARRANTY "Designed to kill you and render the earth uninhabitable, but not guaranteed to do so."  

void printProgramInfo() {  
  Serial.print(COMPANY_NAME);  
  Serial.print(PROG_NAME);  
  Serial.println(VERSION);  
  Serial.println(DEVICE_UNDER_TEST);  
  Serial.println(LICENSE);  
  Serial.println(WARRANTY);  
  Serial.print("Compiled at: ");  
  Serial.println(F(\_\_DATE\_\_ " " \_\_TIME\_\_) ); //compile date that is used for a unique identifier  
}//end printProgramInfo()  



<!--
**ForrestErickson/ForrestErickson** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
