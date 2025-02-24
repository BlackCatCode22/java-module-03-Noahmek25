[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/EV9E9T0q)
# tJavaModule03spr25
tJavaModule03spr25 

Code up these three or four programs and submit source code to your remote repo in GitHub Classroom. Please use the java class file names as specified here. If you know how to zip files, you may also do that as well.

1) package: mystudent; class files: App.java, Student.java - Watch the video "Classes and Objects" and code up everything in the video
public class App {
    public static void main(String [] args) {
}
public class Student{
        String firstName;
        String lastName;
        Double gpa;
        String major;
        int age;
        boolean onProbation;
        
        Student myStudent = new Student(); 
        myStudent.firstName = "Jim";
        myStudent.lastName = "Halpert";
        myStudent.major = "Business";
        myStudent.gpa = 2.3;
        myStudent.age = 24;
        myStudent.onProbation = false;
        
         Student myStudent = new Student(); 
        myStudent2.firstName = "Pam";
        myStudent2.lastName = "Beasley";
        myStudent2.major = "Art";
        myStudent2.gpa = 2.5;
        myStudent2.age = 23;
        myStudent2.onProbation = true;
        
    
        System.out.println(myStudent2.firstName);
    }
}

2) package: mystuff; class files: Driver.java, MyStuff.java - This is the challenge at the end of "Classes and Objects." Your choice of what "object in everyday life" you want to use for this program.

   public class App {
    public static void main(String[] args) {
}
public class Videogame{
        String brand;
        String genre;
        Double score;
        String specialty;
        int age;
        boolean ranked = false;
        
        Videogame myVideogame = new Videogame(); 
        myVideogame.brand = "PlayStation";
        myVideogame.genre = "Shooting game";
        myVideogame.score = "6000.0;
        myVideogame.specialty = "High score";
        myVideogame.age = 20;
        myVideogame.ranked = false;
        
        Videogame myVideogame2 = new Videogame(); 
        myVideogame2.brand = "PlayStation";
        myVideogame2.genre = "Shooting game";
        myVideogame2.score = 5000.0;
        myVideogame2.specialty = "Multiplayer";
        myVideogame2.age = 20;
        myVideogame2.ranked = true;
    
        System.out.println(myVideogame2.brand);
    }
}

3) package: myanimals; class files: Animal.java, Cat.java, Dog.java - Watch the video "Static and the Cat Class" and code up everything to create two subclasses (Cat.java and Dog.java) from the Animal class. Note how the static variable numOfAnimals works in your program. Create an output statement that outputs the current number of animals objects you have whenever a new Dog or Cat object is created. This is how you will know your program is working properly.

4) Advanced (extra credit) - Code up the card game program at the end of Chapter 5 in our textbook.
