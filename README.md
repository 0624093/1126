    class Rectangle implements Shape {
    double Length;
    double width;
    public Rectangle(double l,bouble w){
    this.Length=l;
    this.width=w;}
    public double area(){
        return Length*width;
    }
    
    public String tostring(){
      return "面積="+area();
    }
    }

    class triangle implements Shape {
    double Length2;
    double width2;

    public triangle(double l2,bouble w2){
    this.Length2=l2;
    this.width2=w2;}

    public double area(){
        return Length2*width2;
    }
    

    public String tostring(){
      return "面積="+area();
    }
  

    public static void main(String args[]) {
    
    System.out.println(a1);
    System.out.println(a2);
    }
        }
