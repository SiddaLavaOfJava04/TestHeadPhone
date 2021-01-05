# TestHeadPhone
Design a Java class named TestHeadPhone to represent a headphone set.

/* 
Sidney Beatty
April 23, 2019
File: TestHeadPhone.java
Purpose: Design a Java class named
HeadPhone to represent a headphone 
set.

*/






   public class TestHeadPhone {
  
	public static void main(String[] args)  {   
	
	// Constructing original head phone object 
	
	HeadPhone  headPhoneName = new HeadPhone();
	
	// Call the get method
	   System.out.println("Head phone specs");
	   System.out.println("The head phone manufacturer name is : " + headPhoneName.getManufacturer());
	   System.out.println("The head phone model is : " + headPhoneName.getHeadPhoneModel());
	   System.out.println("The head phone color is : " + headPhoneName.getHeadPhoneColor());
	   System.out.println("Are the head phones plugged in? :" + headPhoneName.getPluggedIn());
	   System.out.println("The head phone volume is : " + headPhoneName.getVolume());
	   
	   
	   //Call the changeVolume method
	    HeadPhone.changeVolume();
		
		
		//Print string method
		System.out.print("Head phone values are:");
		System.out.println(headPhoneName.toString());
		System.out.println("**********************************************************************");
		
		
	  // Constructing new head phone objects
	    HeadPhone bluToothPhones = new HeadPhone();
		
		
		
		// Call the getter methods for bluToothPhones 
		boolean connectionIn = bluToothPhones.getPluggedIn();
		int     bluVolume  = bluToothPhones.getLOW();
		
		// Call the setter methods for bluToothPhones
		String bluManufacturer = "Skull Candy";
		String bluColor        = "Electric Blu";
		String bluPhoneModel   = "Banana Blu";
		
		bluToothPhones.setManufacturer("Skull Candy");
		bluToothPhones.setHeadPhoneColor("Electric Blu");
		bluToothPhones.setHeadPhoneModel("Banana Blu");
		
		// Display BluTooth Phone Specs
	   System.out.println("BluTooth phone specs");
	   System.out.println("The BluTooth head phone manufacturer name is : " + bluManufacturer);
	   System.out.println("The BluTooth head phone model is : " + bluPhoneModel);
	   System.out.println("The BluTooth head phone color is : " + bluColor);
	   System.out.println("Are the head phones paired? :" + connectionIn);
	   System.out.println("The head phone volume is : " + bluVolume);
	   System.out.println("**********************************************************************");
		
		// Constructing new head phone objects
	       HeadPhone extremePhones = new HeadPhone();
		
	
		
		  // Call the setter methods for bluToothPhones
		String extremeManufacturer = "Extreme Beats";
		String extremeColor   = "Rugged Charcoal Black";
		String extremeModel  = "Extreme RockyPhones";
	        boolean ruggedPluggIn = true;
		int    rigidXVolume   = extremePhones.getHIGH(); 
		
		extremePhones.setManufacturer("Extreme Beats");
		extremePhones.setHeadPhoneColor("Rugged Charcoal Black");
		extremePhones.setHeadPhoneModel("Extreme RockyPhones");
		extremePhones.setVolume(rigidXVolume);
		extremePhones.setPluggedIn(ruggedPluggIn);
		
		// Display ExtremePhones Specs
	   System.out.println("ExtremePhones specs");
	   System.out.println("The Extreme head phone manufacturer name is : " + extremeManufacturer);
	   System.out.println("The Extreme head phone model is : " + extremeModel);
	   System.out.println("The Extreme head phone color is : " + extremeColor);
	   System.out.println("Are the head phones plugged in? :" + ruggedPluggIn);
	   System.out.println("The rigidXVolume is : " + rigidXVolume);
