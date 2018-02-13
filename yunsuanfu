import javax.swing.JOptionPane;

public class test1 {
	static int sum=5;
	static int a;
	static int b;
	static int c;
	static int d=0,f=0,r=0,t=0,m,m1,m2,key;	 
	static void logic(int i1,int v)
	{
		 
		  switch(i1)
		         {
		       	
		         case 0:sum=(sum+v);break;
		         case 1:sum=(sum-v);break; 
		         case 2:sum=(sum*v);break;
		         case 3:sum=(sum/v);break; 	 
		       }
}


	public static void main(String args[]) {
	String s1 = null;
	String[] STR = new String[256];
	int[] rekey = new int[256];
	int[] re = new int[256] ;
	String s=JOptionPane.showInputDialog("左值");
	key=Integer.valueOf(s); 
	int value=Integer.valueOf(JOptionPane.showInputDialog("右值"));
	sum=key;
	 for(a=0;a<4;a++)
	 { 
		 logic(a,key);
		 m2=sum;
		 	    
              for( b=0;b<4;b++)
		   	{	
		    	 logic(b,key); 
		    	 m1=sum;
		         for(c=0;c<4;c++)
		          {
		    		logic(c,key);
		            m=sum;
		            for(d=0;d<4;d++)
			          {
			    		logic(d,key);
			    		f++; 
			    	    rekey[r]=sum;
			    		STR[r]="   左: "+key+"    右: " +sum+"    运算符: "+a+" "+b+" "+c+" "+d;
			    		r++;
			            sum=m;
	                  }   
		    	   sum=m1; 		  
		        }
            sum=m2;
		  }
         sum=key;
		}    				 
		     
	for(int i=0;i<256;i++)
	{
	
	if(rekey[i]==value)
		
	{	re[t]=i;
	    t++;
	}
	
		
	}
	
   if(t==0)
		JOptionPane.showMessageDialog(null,"共 0 种情况" );
   if(t>0)
     for(int i1=0;i1<t;i1++)
          s1+="NO. "+i1+STR[re[i1]]+"\n";
          s1=s1.substring(4,s1.length());
	    JOptionPane.showMessageDialog(null,"共"+t+"种情况         0:+  1:-  2:*  3:/        左边优先级高\n"+s1 );
	
   
	}
}
								
						
 

