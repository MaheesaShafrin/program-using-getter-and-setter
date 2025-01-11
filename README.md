# program-using-getter-and-setter
class Student {
private String name;
private int age;
public String getName() {
return name;
}
public void setName(String name) {
this.name = name;
}
public int getAge() {
return age;
}
public void setAge(int age) {
this.age = age;
}
}
public class GetterSetterExample {
public static void main(String[] args) {
Student student = new Student();
student.setName(&quot;Sophia&quot;);
student.setAge(19);
System.out.println(&quot;Name: &quot; + student.getName());
System.out.println(&quot;Age: &quot; + student.getAge());
}
}
Output
Name: Sophia
Age: 19
