🔹 16x16 Multiplier with Hybrid Adders

A 16x16-bit signed multiplier in Verilog using radix-4 Booth multiplication and hybrid adders (CSA + CPA) for fast and efficient computation.

🔹 Features

Inputs: 16-bit signed (two’s complement)

Output range: -1,073,741,824 to +1,073,676,289

Adders: Carry Save Adder (CSA) + Carry Propagate Adder (CPA)

Method: Radix-4 Booth encoding for partial product reduction

🔹 Working  

Booth encoder generates partial products

CSA tree reduces them quickly

CPA performs the final sum

Output is a 32-bit signed product
