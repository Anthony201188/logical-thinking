
# Exercise
    
Look at two laws of Boolean algebra (DeMorgan's Laws):


1. Proof the Demorgan's Laws with Truth Tables
2. For each DeMorgan's Law, write a function that checks the validity of these laws."

## Demorgans law 
  
\
<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">&#xAC;</mi>
  <mo stretchy="false">(</mo>
  <mi>P</mi>
  <mo>&#x2228;</mo>
  <mi>Q</mi>
  <mo stretchy="false">)</mo>
  <mstyle>
    <mspace width="0.278em"></mspace>
  </mstyle>
  <mo stretchy="false">&#x27FA;</mo>
  <mstyle>
    <mspace width="0.278em"></mspace>
  </mstyle>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">&#xAC;</mi>
  <mi>P</mi>
  <mo stretchy="false">)</mo>
  <mo>&#x2227;</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">&#xAC;</mi>
  <mi>Q</mi>
  <mo stretchy="false">)</mo>
</math>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">&#xAC;</mi>
  <mo stretchy="false">(</mo>
  <mi>P</mi>
  <mo>&#x2227;</mo>
  <mi>Q</mi>
  <mo stretchy="false">)</mo>
  <mstyle>
    <mspace width="0.278em"></mspace>
  </mstyle>
  <mo stretchy="false">&#x27FA;</mo>
  <mstyle>
    <mspace width="0.278em"></mspace>
  </mstyle>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">&#xAC;</mi>
  <mi>P</mi>
  <mo stretchy="false">)</mo>
  <mo>&#x2228;</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">&#xAC;</mi>
  <mi>Q</mi>
  <mo stretchy="false">)</mo>
</math>

  


|AND | True | False    
| :--: |:--:| :--:
|True  |True|False
|False |False|False

|OR | True | False
| :--: |:--:| :--:
|True | True| True
|False | True | False  


Equation 1.)\
left side:\
not(True OR True) = not(True) = False

right side:
(not True) AND (not True) = False AND False = False 

Equation 2.)\
left side:\
not(True AND True) = not(True) = False

Right side:\
(not True) or (not True) = (False) OR (False) = False