 # MYfirstDemo
this is my first repository
<br>
Author - Heena Kausar Ansari(1190301)

// "static void main" must be defined in a public class.
public class Main {
    public static void main(String[] args) {
        Scanner scn= new Scanner(System.in);
        
        
        int computerid[]=new computerid[125399];
        int userid[]= new userid[125399];
        int applicationid[]=new applicationid[125399];
        String computertype[]=new computertype[125399];
        String ucomputertype[]=new ucomputertype[125399];
        
        int count=0;duplicate=0;
        for(int i=0;i<125399;i++)
        {
            ucomputertype[i]=computertype[i].toUpperCase(); 
            
        }
        for(int i=0;i<125399;i++)
        {
            for(int j=0;j<125399;j++)
            {
                if(applicationid[j]=374) // To check whether the id=374
                {
                if(compterid[i]=computerid[j] && userid[i]=userid[j] && ucomputertype[i]=ucomputertype[j])
                {
                    count=count+1;
                    duplicate=duplicate+1;
                }
                else if(userid[i]=userid[j] && computerid[i]=computerid[j] && ucomputertype[i]='DESKTOP')
                {
                    count=count+1;
                }
               else if(userid[i]=userid[j] && computerid[i]=computerid[j] && ucomputertype[i]='DESKTOP') 
            }}
            count=count-duplicate+1; 
            duplicate=0; 
        }
        System.out.println("No. of copies of application ID=374 should be bought="+count);
    }
}
