```dart
class About extends Person {
  About(): super(
    name: "NortFox",
    age: Person.rangeAge(20, 21),
    sex: "Male",
    skills: [
      "JavaScript",
      "TypeScript",
      "Dart",
      "React",
      "Next",
      "SCSS",
      "CSS",
      "HTML",
      "Mongoose"
    ],
    interests: [
      "Programming",
      "Game",
      "Astronomy"
    ]
  );

  @override get fullInfo => "Hi, I'm $name, I'm $age and I like ${interests.smartJoin(",", "and")}";
  @override get fullSkills => "My skills ${skills.smartJoin(",", "and")}";
}
```
```dart
void main() {
  var me = About();

  print(me.fullInfo);
  print(me.fullSkills);
}
```
