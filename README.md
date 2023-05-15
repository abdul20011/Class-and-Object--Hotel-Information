# Class-and-Object--Hotel-Information

public class hotel {
	public hotel (String ReservationID, String name, int number, int rate) {
		super();
		this.ReservationID= ReservationID;
		this.name=name;
		this.number=number;
		this.rate=rate;
		this.Subtotal=Subtotal;
		this.tax=tax;
		this.total=total;
	}
private String ReservationID,name;
private int number,Subtotal, tax,total;
int rate;
public String getReservationID() {
	return ReservationID;
}
public void setReservationID(String reservationID) {
	ReservationID = reservationID;
}
public String getName() {
	return name;
}
public void setName(String name) {
	this.name = name;
}
public int getNumber() {
	return number;
}
public void setNumber(int number) {
	this.number = number;
}
public int getRate() {
	return rate;
}
public void setRate(int rate) {
	this.rate = rate;
}
public int getSubtotal() {
	return Subtotal;
}
public void setSubtotal(int subtotal) {
	Subtotal = subtotal;
}
public int getTax() {
	return tax;
}
public void setTax(int tax) {
	this.tax = tax;
}
public int getTotal() {
	return total;
}
public void setTotal(int total) {
	this.total = total;
}
@Override
public String toString() {
	return "hotel [ReservationID=" + ReservationID + ", name=" + name + ", number=" + number + ", rate=" + rate
			+ ", Subtotal=" + Subtotal + ", tax=" + tax + ", total=" + total + "]";
}




}
