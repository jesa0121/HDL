這裡會記錄我學習硬體描述語言的經歷，其中包含從課程習得的VHDL及自學的verilog和system verilog。  

1.Drive and control PLL(ADF4350)。  
首先是FPGA驅動ADF4350。  
從datasheet可得知所需clk及如何傳輸reg訊號。  
再從官網下載ADF模擬軟件，可取得高頻輸出對應的reg。    
ex.欲輸出2G訊號，可得到6組32 bits reg。  


2.Conway's Game of Life  
https://zh.wikipedia.org/zh-tw/%E5%BA%B7%E5%A8%81%E7%94%9F%E5%91%BD%E6%B8%B8%E6%88%8F  
此題取自為HDLBITS，個人覺得相當有趣，在wiki介紹中有影片，像有生命的有機體活動。  
當時在處理二維陣列較為生疏，故使用一維陣列處理。    
去TSRI上完課後，對二維陣列的處理較為成熟，使用二維陣列處理會更加簡單，有時間再寫一次。  
