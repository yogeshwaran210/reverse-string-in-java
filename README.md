# reverse-string-in-java
I have completed reverse  the string in java
public class Main
{
  public static void main (String[]args)
  {
	StringBuilder sbf = new StringBuilder ("welcone Top Freshers");
	  System.out.println (sbf);
	String mystr2 = "Thankyou !";
	  sbf.append (mystr2);
	  System.out.println (sbf);
  }
}

public class Main
{
	public static void main(String[] args) {
	StringBuilder str =new StringBuilder("Tor Freshers");
	System.out.println("String ="+ str.toString());
	StringBuilder reverseStr=str.reverse();
	System.out.println("Reverse String"+ reverseStr.toString());
	}
}
