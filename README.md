# 02-logic
| **Dec. equivalent** | **B[1:0]** | **A[1:0]** | **B is greater than A** | **B equals A** | **B is less than A** |
| :-: | :-: | :-: | :-: | :-: | :-: |
 | 0 | 0 0 | 0 0 | 0 | 1 | 0 |
 | 1 | 0 0 | 0 1 | 0 | 0 | 1 |
 | 2 | 0 0 | 1 0 | 0 | 0 | 1 |
 | 3 | 0 0 | 1 1 | 0 | 0 | 1 |
 | 4 | 0 1 | 0 0 | 1 | 0 | 0 |
 | 5 | 0 1 | 0 1 | 0 | 1 | 0 |
 | 6 | 0 1 | 1 0 | 0 | 0 | 1 |
 | 7 | 0 1 | 1 1 | 0 | 0 | 1 |
 | 8 | 1 0 | 0 0 | 1 | 0 | 0 |
 | 9 | 1 0 | 0 1 | 1 | 0 | 0 |
 | 10 | 1 0 | 1 0 | 0 | 1 | 0 |
 | 11 | 1 0 | 1 1 | 0 | 0 | 1 |
 | 12 | 1 1 | 0 0 | 1 | 0 | 0 |
 | 13 | 1 1 | 0 1 | 1 | 0 | 0 |
 | 14 | 1 1 | 1 0 | 1 | 0 | 0 |
 | 15 | 1 1 | 1 1 | 0 | 1 | 0 |
 
 
 graterSOP/min= ()
 
 
 

## 2. 2-bit comparator 

### The K-map for the "equals" function is as follows:

![Kmap1](mapa.png)

### The K-map for the "less" function is as follows:

![Kmap2](mapa1.png)


**rovnica:**
 
*  (B̅1+A1)*(B̅0+A1)*(B̅1+B̅0)*(A1+A0)*(B̅1+A0) * 




### The K-map for the "grater" function is as follows:


![Kmap2](mapa2.png)

### 4-bit Comparator
#### CODE of design.vhdl
```
library ieee;
use ieee.std_logic_1164.all;

------------------------------------------------------------------------
-- Entity declaration for 2-bit binary comparator
------------------------------------------------------------------------
entity comparator_4bit is
    port(
        a_i           : in  std_logic_vector(4 - 1 downto 0);
        b_i           : in  std_logic_vector(4 - 1 downto 0);


        -- COMPLETE THE ENTITY DECLARATION
        
        B_greater_A_o    	: out std_logic;
		B_equals_A_o    	: out std_logic;
        B_less_A_o   	 	: out std_logic       -- B is less than A
    );
end entity comparator_4bit;

------------------------------------------------------------------------
-- Architecture body for 2-bit binary comparator
------------------------------------------------------------------------
architecture Behavioral of comparator_4bit is
begin
	B_greater_A_o   <= '1' when (b_i > a_i) else '0';
    B_less_A_o   	<= '1' when (b_i < a_i) else '0';
	B_equals_A_o    <= '1' when (b_i = a_i) else '0';

    -- WRITE "GREATER" AND "EQUALS" ASSIGNMENTS HERE


end architecture Behavioral;

```

