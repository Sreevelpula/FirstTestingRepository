import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;  
import org.openqa.selenium.WebElement;
import org.openqa.selenium.firefox.FirefoxDriver;


 public class Opengoogle {  
 public static void main(String args[]){ 
	 
	     // in the path , given \\ double lines
   System.setProperty("webdriver.gecko.driver","C:\\Temp\\geckodriver-v0.10.0-win64\\geckodriver.exe" );
	 
   FirefoxDriver driver=new FirefoxDriver();  
   driver.get("http://facebook.com");  // to open URL
   System.out.println(driver.getTitle());// to get title of the page
   System.out.println(driver.getCurrentUrl());// to verify whether opened URL is correct? or not? 
   driver.close(); // this command closes particular browser
