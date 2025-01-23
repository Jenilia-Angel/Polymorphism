public class Main {
    public int addition(int x,int y){
        return x+y;
    }
    public int addition(int x, int y, int z){
    return x+y+z;
    
}
    public double addition(double x, double y){
        return x+y;
    }
    public static void main(String[] args) {
        Main number = new Main();
        int res1=number.addition(26,06);
        System.out.println("Addition of two integers:" +res1);
        int res2=number.addition(26,06,8);
        System.out.println("Addition of three integers:"+res2);
        double res3 = number.addition(26.04,06.12);
        System.out.println("Addition of two doub;es:"+res3);
        
        
    }
    
}

Output:

Addition of two integers:32
Addition of three integers:40
Addition of two doub;es:32.16


