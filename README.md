# string1
remove characters from number string in java
public class Removechar{
 public static String convert(String str)
 {
    StringBuffer sb=new StringBuffer(str);
    for(int i=0;i<=sb.length();i++)
     {
        if(sb.charAt[i]<48||sb.charAt[i]>57)
         {
            sb.deleteCharAt[i];
            i--;
         }
      }
    return sb.toString();
 }   
    

{
  public ststic void main(String args[])
    {
       String str="9444q78gh63";
       str=convert(str);
       System.out.println(str);
     }
 } 
 }
