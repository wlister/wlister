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
