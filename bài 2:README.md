public class Rectangle {
    // Attributes
    private double area;
    private double length;
    private double perimeter;
    private double width;

    // Constructor
    public Rectangle(double length, double width) {
        this.length = length;
        this.width = width;
    }

    // Methods
    public void calcArea() {
        area = length * width;
    }

    public void calcPerimeter() {
        perimeter = 2 * (length + width);
    }

    public double getArea() {
        return area;
    }

    public double getPerimeter() {
        return perimeter;
    }

    public void setLength(double length) {
        this.length = length;
    }

    public void setWidth(double width) {
        this.width = width;
    }
}
