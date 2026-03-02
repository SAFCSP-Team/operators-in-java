public class OperatorsProject {
    public static void main(String[] args) {

        double price = 100.0;
        int quantity = 3;
        boolean couponActive = true;

        double total = price * quantity;
        System.out.println("Total before tax: " + total);

        total = total * 1.15;
        System.out.println("Total after tax: " + total);

        boolean freeShipping = total > 300 || couponActive;
        System.out.println("Free shipping: " + freeShipping);

        boolean vipBuyer = quantity >= 4 && total > 350;
        System.out.println("VIP buyer: " + vipBuyer);
    }
}
