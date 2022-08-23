# Test-Class-Two
package com.yourlogo.pages;

import org.openqa.selenium.By;
import org.openqa.selenium.Keys;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class TestClass2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.setProperty("webdriver.chrome.driver", "C:\\Users\\Gomotse\\Documents\\selenium-java-4.4.0\\chromedriver.exe");
		WebDriver driver = new ChromeDriver();
		driver.get("http://automationpractice.com/");
		//driver.navigate().to("http://automationpractice.com/");
       driver.findElement(By.name("search-mystore")).sendKeys("summerdress", "T-shirts", "Tops" + Keys.ENTER);
       
		
	}

}
