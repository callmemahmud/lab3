#for_8X1_MUX_module(not_textbech)


module mux8to1(out,in0,in1,in2,in3,in4,in5,in6,in7,s0,s1,s2);
output out;
input in0,in1,in2,in3,in4,in5,in6,in7;
wire m,n;

mux4to1 a(m,i0,i1,i2,i3,s0,s1);
mux4to1 b(n,i4,i5,i6,i7,s0,s1);
mux4to1 c(out,m,n,0,0,s1,s2);
endmodule
