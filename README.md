# Sum-of-the-digits-
Public class Thesumoftheditsofanumber{

    Public static void main(String[] args) {
        
     int num=25,rem=0,sum=0,temp;
     
        temp=num;
        
        while(num>0)
        {
            rem=num%10;
            sum=sum+rem;
            
            num=num/10;
        }


        System.out.println(" Sum of the digits of " + temp + " is " + sum);
        
    }
    
}

OUTPUT:

 Sum of the digits of 25 is 7
 
