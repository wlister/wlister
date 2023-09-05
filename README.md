# Hi there

module top_module (
    input clk,
    input reset,
    output [9:0] q);
	
    always_ff@(posedge clk) begin
        if(reset || q == 999) begin
            q <= 10'b0000000000;
        end
        else begin
            q <= q + 10'b0000000001;
        end
    end
endmodule
