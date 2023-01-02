```java
public class Ingmar extends GitHubUser {
    public Ingmar() {
    super("Ingmar van Busschbach", "Netherlands");

    this.addLanguage("C#", "C++", "Javascript", "HTML", "CSS", "HLSL", "Dutch", "English", "German");
    this.addDiscipline("Unreal Engine", "Unity", "Game Designer", "Systems Designer", "Level Designer", "Gameplay Programmer", "Systems programmer", "Shader      Programmer", "Procedural Art Programmer");
    }
}

public abstract class GitHubUser {

    private final String name;
    private final String country;

    private ArrayList<String> languages = new ArrayList<>();
    private ArrayList<String> disciplines = new ArrayList<>();

    public GitHubUser(String name, String country) {
        this.name = name;
        this.country = country;
    }

    public void addLanguage(String... language) {
        languages.addAll(language);
    }
    public void addDiscipline(String... discipline) {
        disciplines.addAll(discipline);
    }
}
```

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Ingmar-van-Busschbach&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
  </tr>
</table>
