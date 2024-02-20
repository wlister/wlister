# Hi there!

<p align="center">
  <img src="https://64.media.tumblr.com/e1b3e9193163209d82b4bdbdc7dec2c2/tumblr_oloo8iEntd1uce9bao2_r1_540.gif" alt="animated" />
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
