# Lab-1-webwork
The basic code of php and make class and functions 
_______________________


<?php
// =========================
// Part A + B + C ===> in this docs I did the three of thr first part 
		=====> paper by mohammad zaman rezayee
// =========================
class Student
{
    // Properties
    public $name;
    public $studentId;
    public $department;
    // Constructor
    function __construct($name, $studentId, $department)
    {
        $this->name = $name;
        $this->studentId = $studentId;
        $this->department = $department;
    }
    // Method
    function sayHello()
    {
        echo "Hello! I am a student.<br>";
    }
    // Method
    function showInfo()
    {
        echo "Name: " . $this->name . "<br>";
        echo "Student ID: " . $this->studentId . "<br>";
        echo "Department: " . $this->department . "<br>";
    }
}
// Object 1
$student1 = new Student(
    "Ahmad",
    1001,
    "Computer Science"
);
$student1->sayHello();
$student1->showInfo();
echo "<hr>";
// Object 2
$student2 = new Student(
    "Sara",
    1002,
    "Information Systems"
);
$student2->showInfo();
// =========================

may be have alot of mistake I hope it be 
acceptable thanks 
?>
_______________ Mohammad Zaman Rezayee _____
