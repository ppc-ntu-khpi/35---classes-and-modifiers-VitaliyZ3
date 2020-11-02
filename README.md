# Classes and modifiers 

### Customer.java
```java
public class Сustomer {
	private int ID;
	private boolean isNew = true;
	private double total = 1000;
	
public Сustomer() {
		super();
		this.ID = 1;
    this.isNew = true;
    this.total = 1000;
	}

  public int getID() {
		return ID;
	}

	public void setID(int iD) {
		ID = iD;
	}

	public boolean isNew() {
		return isNew;
	}

	public void setNew(boolean isNew) {
		this.isNew = isNew;
	}

	public double getTotal() {
		return total;
	}

	public void setTotal(double total) {
		this.total = total;
	}

	public void displayCustomerInfo() {
		System.out.println("ID is " + this.ID);
		System.out.println("Is new: " + this.isNew);
		System.out.println("Total is " + this.total);
	}
}```


### CustomerTest.java
```java
public class CustomerTest {

	public static void main(String[] args) {
		Сustomer c = new Сustomer();
    c.setID(1);
    c.setNew(false);
    c.setTotal(1.1);
    c.displayCustomerInfo();
	}

}```

## Скріншоти роботи програми
![](https://github.com/ppc-ntu-khpi/35---classes-and-modifiers-VitaliyZ3/blob/main/Solution/HAIPOVO.png)
