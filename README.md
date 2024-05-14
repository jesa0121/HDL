
這裡會記錄我學習硬體描述語言的經歷，其中包含從課程習得的VHDL及自學的verilog和system verilog。


首先是FPGA驅動ADF4350。
從datasheet可得知所需clk及如何傳輸reg訊號。
再從官網下載ADF模擬軟件，可取得高頻輸出對應的reg。  
ex.欲輸出2G訊號，可得到6組32 bits reg。
