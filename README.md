$EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit. 
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

APPARATUS REQUIRED:
S.No.	Components	Range	Quantity
1	Resistor	1kΩ	3
2	Voltmeter (DC)	0-30V	3
3	Ammeter (DC)	(0-200)mA	3
4	Bread Board		1
5	Regulated Power Supply	(0-30)V	1
6	Connecting wires		As required

THEORY:
KVL: Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.
KCL:
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative


PROCEDURE:
a.   KVL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the voltmeter connected across each resistor.
7.   Take readings for different values of input voltage and tabulate them.


b.  KCL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the ammeter connected to each resistor.
7.   Take readings for different values of input voltage and tabulate them. 
CIRCUIT DIAGRAM:

CIRCUIT DIAGRAM:
a.   KVL:
<img width="1116" height="686" alt="KVL" src="https://github.com/user-attachments/assets/8f568c2d-1b34-40d6-8f95-44555f1ef692" />
b.  KCL: 
<img width="1514" height="834" alt="KCL" src="https://github.com/user-attachments/assets/32254794-aa50-4c3a-a128-293cda785720" />
Calculation:
a.   KVL:

$$V=V_1+V_2+V_3$$

$$100=IR_1+IR_2+IR_3$$

$$R_{eq}=R_1+R_2+R_3$$

$$R_{eq}=180$$

$$I=V/R_{eq}=100/180$$

$$I=0.556A$$

$$V_1=IR_1=0.556\times30=16.68V$$

$$V_2=IR_2=0.556\times50=27.8V$$

$$V_3=IR_3=0.556\times100=55.6V$$

$$100V=16.68V+27.8V+55.6V$$

$$100V=100V$$

$$Hence Proved$$
b.  KCL:
$$I_{30\Omega}=I_{50\Omega}+I_{100}\Omega$$
$$I_{30}\Omega=(100-V)/30$$
$$I_{50}\Omega=V/50$$
$$I_{100}\Omega=V/100$$
$$(100-V)/30=V/50+V/100$$
$$V=52.63V$$
$$I_{30}\Omega=(100-52.63)/30=1.58A$$
$$I_{50}\Omega=52.63/50=1.05A$$
$$I_{100}\Omega=52.63/100=0.53A$$
$$-1.58A+1.05A+0.53A=0A$$
$$Hence Proved$$

Tabulation:

a.   KVL:
 |KVL|SOURCE(V)|$$V_30\Omega$$|$$V_50\Omega$$|$$V_100\Omega$$|$$V_30\Omega+V50\Omega+V_100\Omega(V)$$|
 |---- |-----|----|----|---|-----|
 |Theoretical|100|16.68|27.8|55.6|100.05|
 |Practical|100|16.68|27.8|55.6|100.08|

b.  KCL:
|KCL|$$I_30\Omega$$|$$I_50\Omega$$|$$I_100\Omega$$|VA|
|----|----|----|-----|----|
|Theoretical|-1.58A|1.05A|0.53A|52.63A|
|practical|-1.58A|1.05A|0.53A|52.63A|

RESULT:
Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.
