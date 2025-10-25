# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**




**To measure RTh or RN**


<img width="291" height="113" alt="Screenshot 2025-10-25 181016" src="https://github.com/user-attachments/assets/c2cb37c8-8177-47c4-ace0-37b96a97b921" />





**To measure IN or Isc**

<img width="383" height="158" alt="Screenshot 2025-10-25 181117" src="https://github.com/user-attachments/assets/c9ee2d4d-349b-44f8-98f1-1c405a6c87d1" />


 
**Thevenin’s equivalent circuit**


<img width="342" height="192" alt="Screenshot 2025-10-25 181355" src="https://github.com/user-attachments/assets/f5cab49a-1aee-4675-9988-6b4c150aa028" />



**Norton’s equivalent circuit**


<img width="319" height="194" alt="image" src="https://github.com/user-attachments/assets/b0e9be8b-1332-471c-9d99-2b4e60e3ad3c" />



**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**


<img width="237" height="148" alt="Screenshot 2025-10-25 183230" src="https://github.com/user-attachments/assets/b5ab906f-8baa-41bb-975a-35b4db75ca33" />

To measure I L

Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

<img width="250" height="134" alt="Screenshot 2025-10-25 183350" src="https://github.com/user-attachments/assets/d29017ed-c9ae-488c-8fca-87d688105824" />


To measure RTh or RN

Vi (volts)	RTh (Ω)


**TABULAR COLUMN:3**

<img width="273" height="152" alt="Screenshot 2025-10-25 183430" src="https://github.com/user-attachments/assets/112171d9-3f2e-40e3-927d-3ca53a1462b9" />


To measure IN or Isc

Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:

 <img width="257" height="480" alt="Screenshot 2025-10-25 181526" src="https://github.com/user-attachments/assets/954d4b09-baf8-41f1-8265-189b59fd27d9" />



**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
