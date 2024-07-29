# overriding-demo2
package com.qis.corejava.final1;
final class Myclass2{
  	 public void mydata() {
			System.out.println("super  class Myclass method");
		} 
 }
public class OverridingDemo2 //extends Myclass2
{	
	public void mydata1() {
		System.out.println("sub class mydata method");
	}
	public static void main(String[] args) {
		OverridingDemo2 od= new OverridingDemo2();
		od.mydata1();
	}

}
