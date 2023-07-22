# Launch-Cromedrivers-projects

package launchbrowser;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.chrome.ChromeOptions;
import org.openqa.selenium.remote.RemoteWebDriver;
import org.zeromq.ZStar.Set;

public class launchchromebrowser {
	
	public static void main(String[] args) {
		
		ChromeOptions options = new ChromeOptions();
		//options.addArguments("--disable-notifications");
		options.addArguments("--disable-notifications");
		
		WebDriver driver = new ChromeDriver(options);
		driver.manage().window().maximize();
		/*driver.get("https://www.facebook.com");
		//driver.findElement(By.xpath("//input[@id=\"identifierId\"]")).sendKeys("hatekarakshay01@gamil.com");
		//driver.findElement(By.xpath("//span[text()='Next']")).click();
		driver.findElement(By.xpath("//input[@id=\"email\"]")).sendKeys("8975328532");
		driver.findElement(By.xpath("//input[@id=\"pass\"]")).sendKeys("******");
		//driver.findElement(By.xpath("//button[@id=\"u_0_5_B3\"]")).click();
		//driver.findElement(By.xpath("//div[@id=\"u_0_5_B3\"]")).click();
		driver.findElement(By.xpath("//button[text()='Log in']")).click();
		//driver.findElement(By.xpath("//button[text()='Block']")).click();
		//driver.findElement(By.cssSelector("div[aria-label='Close']")).click();
		//driver.findElement(By.id("//button[text()='Block']")).click();
		
		
		//String parent = driver.getWindowHandle();

		*/
		driver.get("https://kotakbank456--kotakuat.sandbox.my.salesforce.com/?ec=302&startURL=%2Fvisualforce%2Fsession%3Furl%3Dhttps%253A%252F%252Fkotakbank456--kotakuat.sandbox.lightning.force.com%252Flightning%252Fr%252FCLOS_Party__c%252Fa15C3000000FVjRIAW%252Fview");
		driver.findElement(By.xpath("//input[@id=\"username\"]")).sendKeys("vijayshankar.s@yethi.co.in");
		driver.findElement(By.xpath("//input[@id=\"password\"]")).sendKeys("Laxmi@0123");
		driver.findElement(By.xpath("//input[@id=\"Login\"]")).click();
		driver.findElement(By.xpath("//link[text()='Loan Applications']")).click();
		
		
	}
}
