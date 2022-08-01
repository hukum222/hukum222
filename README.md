- 👋 Hi, I’m @hukam222
- 👀 I’m interested in doing coding
- 🌱 I’m currently learning full stack web development
- 📫 How to reach me via linkdin/https://www.linkedin.com/in/hukam-singh31/

<!---
hukum222/hukum222 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->





//factrorial of ncr..


import java.util.*;
public class Main
{ 
    public static int factorial(int num){
        
        int result = 1;
        while(num>0){
            
            result *=num;
            num--;
            
        }
        return result;
        
        
    }
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    
	    int n = sc.nextInt(),r = sc.nextInt();
	    int nf = factorial(n);
	    int rf = factorial(r);
	    int nfr = factorial(n-r);
	    
	    System.out.println(nf/(rf*nfr));
	    
		
		
		
	}
}

