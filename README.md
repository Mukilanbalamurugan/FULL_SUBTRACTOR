# FULL_SUBTRACTOR
# AIM:
To simulate and synthesis of Full subtractor using Vivado software.
# APPARATUS REQUIRED:
Vivado 2023.1 software.
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)
# Program:
    module full_subtractor(a, b, c, D, Bout);
    input a, b, c;
    output D, Bout;
    assign D = a ^ b ^ c ;
    assign Bout = ~a & (b^c) | b & c;
    endmodule
  # Elaborated Design:
  <img width="960" alt="Screenshot 2024-03-25 221821" src="https://github.com/DeepanAnbazhagan/FULL_SUBTRACTOR/assets/164902865/b162f3b9-d9ff-44f9-99cc-d7e4875a746c">
  
  # Output: 
  ![fullsubtractor pic](https://github.com/Mukilanbalamurugan/FULL_SUBTRACTOR/assets/159005942/3a9e4064-bc06-470c-9c28-a743810f8060)

  
  # RESULT:
Thus the simulate and synthesis of Full subtractor is verified successfully by using Vivado software.




