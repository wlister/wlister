# Hi there!

<p align="center">
  <img src="https://24.media.tumblr.com/78b7de068a496b13555094a4cf30ceb5/tumblr_mta8to65Nw1rlcjydo1_500.gif" alt="animated" />
</p>

```verilog
module top_module (
    input clk,
    input reset,
    output [9:0] q);
	
    always_ff@(posedge clk) begin
        if(reset || q == 999) begin
            q <= 10'd0;
        end
        else begin
            q <= q + 10'd1;
        end
    end
endmodule
```
<div align="center">
	<code><img width="100" src="https://upload.wikimedia.org/wikipedia/en/e/ef/SystemVerilog_logo.png" alt="SystemVerilog" title="SystemVerilog"/></code>
	<code><img width="100" src="https://www.sarsen.net/uploads/files/images/Intel%20FPGA%20Logo.png" alt="FPGA" title="FPGA"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/117201156-9a724800-adec-11eb-9a9d-3cd0f67da4bc.png" alt="Java" title="Java"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/192106070-46255bcf-65e6-4c6b-a296-bf8d0d8fb2a7.png" alt="C" title="C"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/192106073-90fffafe-3562-4ff9-a37e-c77a2da0ff58.png" alt="C++" title="C++"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183896128-ec99105a-ec1a-4d85-b08b-1aa1620b2046.png" alt="MySQL" title="MySQL"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python"/></code>
</div>
