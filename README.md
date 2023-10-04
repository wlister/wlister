# Hi there!

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
