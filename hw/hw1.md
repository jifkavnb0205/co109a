#第一週  
--------------------------------
##And  
--------------------------------

CHIP And {
    IN a, b;
    OUT out;

    PARTS:
    // Put your code here:
    Nand(a=a, b=b, out=AnandB);
    Not(in=AnandB, out=out);
}