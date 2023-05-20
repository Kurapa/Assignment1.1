# Assignment1.1
//using recursion
public class pascal1{
public static void main(String[] args) { int a=10;

for(int i=1;i<=a;i++){ for(int j=1;j<=1;j++){ System.out.print(pas(i,j)+" ");

} System.out.println();

}

static int pas(int a,int b){

if(b==1 || a==b){

return 1;

}

return pas(a-1,b-1)+pas (a-1,b);
}
}
