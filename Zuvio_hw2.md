```java
import java.util.ArrayList;
import java.util.List;
```
```java
public class Student{
    private String name;
    private List<Course> course;

    public Student(String name){
      this.name = name;
      this.courses = new ArrayList<>();
    }

    public boolean addCourse(Course course){
        if (course.size() < 10)
            course.add(course);
            return ture;
        }
        return false;
    }
    public boolean removeCourse(Course course){
        return course.remove(course)
    }
    public List<Course> getCourse(){
        return courses;
    }
    // Other getters, setters, and relevant methods
}
```
```java
public class Course{
    privater String courseName;
    public Course (String courseName){
        this.courseName = courseName;
    }
    //Getters, setters, and other relevaant methods
}


```
