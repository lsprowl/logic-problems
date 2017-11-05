# Twelve Marble Answer

Yes, it is possible to identify the flawed marble and determine if it is 
heavier or lighter than the other marbles with only three weighings on the 
balance scale. Assigning each marble a letter A-L, the following procedure will 
determine which marble is flawed and if it is heavier or lighter.

1. ABCD vs EFGH
  * balanced: IJKL is flawed
    2. ABC vs IJK
      * balanced: L is flawed
        3. A vs L
          * unbalanced with L heavier: **L flawed heavier**
          * unbalanced with L lighter: **L flawed lighter**
      * unbalanced with IJK heavier: IJK flawed heavier
        3. I vs J
          * balanced: **K flawed heavier**
          * unbalanced with I heavier: **I flawed heavier**
          * unbalanced with J heavier: **J flawed heavier**
      * unbalanced with IJK lighter: IJK flawed lighter
        3. I vs J
          * balanced: **K flawed lighter**
          * unbalanced with I lighter: **I flawed lighter**
          * unbalanced with J lighter: **J flawed lighter**
  * unbalanced with ABCD heavier: either ABCD flawed heavier or EFGH flawed lighter
    2. ABCE vs DJKL
      * balanced: FGH flawed lighter
        3. F vs G
          * balanced: **H flawed lighter**
          * unbalanced with F lighter: **F flawed lighter**
          * unbalanced with G lighter: **G flawed lighter**
      * unbalanced with ABCE heavier: ABC heavier
        3. A vs B
          * balanced: **C flawed heavier**
          * unbalanced with A heavier: **A flawed heavier**
          * unbalanced with B heavier: **B flawed heavier**
      * unbalanced with DJKL heavier: D heavier or E lighter
        3. L vs D:
          * balanced: **E flawed lighter**
          * unbalanced with D heavier: **D flawed heavier**
  * unbalanced with ABCD lighter: either ABCD flawed lighter or EFGH flawed heavier
    2. ABCE vs DJKL
      * balanced: FGH flawed heavier
        3. F vs G
          * balanced: **H flawed heavier**
          * unbalanced with F heavier: **F flawed heavier**
          * unbalanced with G heavier: **G flawed heavier**
      * unbalanced with ABCE lighter: ABC lighter
        3. A vs B
          * balanced: **C flawed lighter**
          * unbalanced with A lighter: **A flawed lighter**
          * unbalanced with B lighter: **B flawed lighter**
      * unbalanced with DJKL lighter: D lighter or E heavier
        3. L vs D:
          * balanced: **E flawed heavier**
          * unbalanced with D lighter: **D flawed lighter**
