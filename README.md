Allan_SM_CPU
============
-- if read_complete = '1' then MEA_Register gets read_data from RAM. Depending on CPU	                  
mux

process(clk) begin
if rising_edge(clk) then 
if Enable_Adress_MEA <= '1' then
  address <= MEA_Register;	
 elsif 	

process(clk) begin
if rising_edge(clk) then 
if Enable_MEA_Gets_Read_Data <= '1' then
  MEA_Register <= Read_DAta;	
  elsif

                  	                    -
io_address <= IREG(5 downto 3);                                         -- Io Address always gets IREG(5 downto 3)		                  
IREG <= read-data;

process (clk) begin                                                     -- IREG, Enables
    if rising_edge(clk) then
      Ram_REady ='1' then
      IReg <= read_data;
      if
      
 process (clk) begin                                                     -- IREG, Enables
    if rising_edge(clk) then
      Enable_Clear_link ='1' then
      L_REG <= 0;
      if
           
      
process (clk) begin                                                    --- AC REgister, Enables
   if rising _edge(clk) then
     if enable_and = '1' then
       Ac <= AC and IREG;
       if Enable_Ac_clear = '1' then
        AC _REG <= "000000000000";
        IF enable_rotae_right = '1' then
          AC_REG <= 
          if enable_rotate_left = '1' then
          AC_
        
      if en
