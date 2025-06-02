# Student-Registration-System
Student Registration System:
class Student {
    String studentId;
    String name;
    Account account;

    public Student(String studentId, String name, Account account) {
        this.studentId = studentId;
        this.name = name;
        this.account = account;
    }
}

class Account {
    String username;
    String password;

    public Account(String username, String password) {
        this.username = username;
        this.password = password;
    }
}

class Course {
    String courseId;
    String courseName;

    public Course(String courseId, String courseName) {
        this.courseId = courseId;
        this.courseName = courseName;
    }
}

class RegistrationManager {
    public void register(Student student, Course course) {
        System.out.println(student.name + " registered for " + course.courseName);
    }
}
