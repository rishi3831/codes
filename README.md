public class varargs {
    static void maxno(int...x){
        if(x.length==0){
            System.out.println("no number is input");
        }
        int m=x[0];
        for(int i=0;i<x.length;i++){
            if(x[i]>m){
                m=x[i];
            }
        }
        System.out.println(m);
    }
    public static void main(String[] args) {
        maxno(10,21);
maxno(11,23,43);
    }
}
