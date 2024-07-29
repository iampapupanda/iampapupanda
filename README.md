Write a Java program to create two interfaces, Printable with a method print() that takes no arguments and returns void, and 
Showable with a method show() that takes no arguments and returns void. 
Create a Document class that implements both the interfaces and override print() and show() methods.
interface Printable{  
void print();  
}  
interface Showable{  
void show();  
}  
class Document implements Printable,Showable{  
public void print(){System.out.println("Hello");}  
public void show(){System.out.println("Welcome");}  
  
public static void main(String args[]){  
Document obj = new Document();  
obj.print();  
obj.show();  
 }  
} 
