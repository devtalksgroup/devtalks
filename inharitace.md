# Inharitance

Classes can reuse code and properties from other classes. Relationships and subclasses between objects can be assigned, enabling developers to reuse common logic, while still maintaining a unique hierarchy. Inheritance forces more thorough data analysis, reduces development time and ensures a higher level of accuracy.

__Example in Java:__

Shape.java file
```
class Shape {
    String name;
    Shape() {
        this.name = "Shape";
    }
    void draw() {
        System.out.printf("draw %s", name);
    }
}
```
Circle.java file
```
class Circle extends Shape {
    public Circle() {
        name = "Circle";
    }
}
```

__Usage:__

Main.java file
```
class Main {
    public static void main(String[] args) {
        Shape shape = new Circle();
        shape.draw();
    }
}
```