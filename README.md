# Member_class
# Java-Experiment-10

# Inheritance

# Aim:
           To write a Java program to Create a class named 'Member' having certain members.

# Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Employee" and create required statements.

Step 3 : Create a another class called "Manager" and create required statements.

Step 3 : Create another class,called the "Member" and create required statements

Step 4 : Create a main class,called the "Solution".

Step 5 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 6 : Display the statements from the first and secomd Class using Solution Class in the terminal.

# Program

~~~
public class Employee extends Member {
    public String specialization;
}
public class Manager extends Member {
    public String departemnt;
}
public class Member {
    public String name;
    public int age;
    public String ph;
    public String address;
    public String sal;
    public void dissal() {
        System.out.println("The Salary of this employee is: " + sal);
    }
}
public class Type {
    public static void main(String[] args) {
        Total emp1 = new Total();
       Proanddiff emp2 = new Proanddiff();
        emp1.name = "Sham";
        emp1.age = 20;
        emp1.ph = "8610750378";
        emp1.address = "Salem";
        emp1.sal = "900k";
        emp2.departemnt = "AI-DS";
        emp1.specialization = "Data Analyst";
        System.out.println(emp1.name + "\n" + emp1.age + "\n" + emp1.ph + "\n" + emp1.address
                           + "\n" + emp1.specialization + "\n" + emp2.departemnt);
        emp1.dissal();

    }
}
~~~
# Output:


![image](https://github.com/Poojariyaa/Member_class/assets/127511817/193ae0e3-441b-4ec7-abd6-ea779f9006ff)


# Result
        We have successfully created a Java program using inheritance one class can acquire the properties of others.


