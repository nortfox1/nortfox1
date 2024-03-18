```dart
class About extends Person {
  About(): super(
    name: "San Krayer",
    age: Person.rangeAge(22, 23),
    sex: "Male",
    special: "Fox",
    skills: [
      "TypeScript",
      "Dart",
      "React",
      "Next",
      "SCSS",
      "CSS",
      "HTML",
      "Mongoose",
      "Firebase"
    ],
    interests: [
      "Programming",
      "Game",
      "Astronomy"
      "Furry"
      "Science"
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
<details> 
  <summary>💻 Статистика профиля GitHub</summary>
  <br/>
    <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="DenverCoder1's Github Stats" src="https://denvercoder1-github-readme-stats.vercel.app/api/?username=nortfox1&show_icons=true&count_private=true&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866" height="192px"/></a>
  <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="DenverCoder1's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nortfox1&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866&hide=Jupyter%20Notebook" height="192px"/></a>
  <br/>
</details>
