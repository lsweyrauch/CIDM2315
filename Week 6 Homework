Professor p1 = new Professor();
        p1.name = "Alice";
        p1.classTeach = "Java";
        p1.setShowSalary(9000);
        p1.ProfessorInfo();
        p1.newsalary = 9000;

        Professor p2 = new Professor();
        p2.name = "Bob";
        p2.classTeach = "Math";
        p2.setShowSalary(8000);
        p2.newsalary = 8000;
        double salarydifference = (p1.newsalary - p2.newsalary);

        Student s1 = new Student();
        s1.name = "Lisa";
        s1.enroll = "Java";
        s1.setshowGrade(90);
        s1.StudentInfo();
        s1.TotalGrade = 90;

        Student s2 = new Student();
        s2.name = "Tom";
        s2.enroll = "Math";
        s2.setshowGrade(80);
        s2.StudentInfo();
        s2.TotalGrade = 80;
        double gradetotal = (s1.TotalGrade + s2.TotalGrade);

        Console.WriteLine($"The difference in salary between {p1.name} and {p2.name} is: {salarydifference}");
        Console.WriteLine($"The total grade of {s1.name} and {s2.name} is: {gradetotal}");

class Professor{

    public string name;

    public string classTeach;

    private double salary;

    public double new_salary;

    public double getShowSalary(){
        return salary;
    }
    public void setShowSalary(double newsalary){
        salary = newsalary;
    }
    public double newsalary;


    public void ProfessorInfo(){
        Console.WriteLine($"Professor {name} teaches {classTeach}, and the salary is: {salary}");
    }
}

class Student{

    public string name;

    public string enroll;

    private double grade;

    public void StudentInfo(){
        Console.WriteLine($"Student {name} enrolls in {enroll}, and the grade is: {grade}");
    }

    public double getshowGrade(){
        return grade;
    }

    public double TotalGrade;
    
    public void setshowGrade(double newgrade){
        grade = newgrade;
    }

    
}
