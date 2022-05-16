### Hi there 👋

<!--
**Rodolfo-Justina/Rodolfo-Justina** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![Working From Home](wfh-banner.png)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=Rodolfo-Justina)

```java
import java.util.Arrays;
import java.util.function.Function;

/**
 * @author Rodolfo Justina
 * @since 2022/05/16
 * @version 1.0.0
 */
public class ApplicationDeveloper {
    
    public static void main(String[] args) {

        String name = "Rodolfo Faquin Della Justina";
        String role = "Application Developer";
        String[] languageSpoken = {"pt_BR", "en_US"};
        String[] principalSkils = {"Java", "Docker", "SQL", "Angular", "TypeScript", "Android", "Cloud"};
        
        Function<String[], String> skills = f -> {
            String allSkillsTogether = "";
            for(String skill : Arrays.asList(f)) {
                allSkillsTogether+= "\n\t- " + skill;
            }
            return allSkillsTogether;
        };

        StringBuilder aboutMe = new StringBuilder();
        aboutMe.append("Hi, I'm ").append(name).append(". Is a pleasure to have you here!")
        .append("\n\n")
        .append("I have a degree in information system, a pos-graduationg in engineering ")
        .append("and architecture of software and master degree in technology of information and communications.")
        .append("\n\n")
        .append("I started my job career in 2010 as an Android Application Developer, in 2012 I worked as System Analist, ")
        .append("in 2017 I founded my startup ended it in 2020 where I started as Java Senior Develop in a global company. ")
        .append("my main role is to be an ").append(role).append(" at IBM.")
        .append("\n\n")
        .append("My principal skills are:").append(skills.apply(principalSkils))
        .append("\n\n")
        .append("As a friendly brazilian are, I love to talk and to meet new people. ")
        .append("My native language is Portuguese(").append(languageSpoken[0])
        .append(") and my second language is English(").append(languageSpoken[1]).append(").");
        
        System.out.println(aboutMe);
    }
    
}
```

## 🤖 Technologies & Tools

![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=FCC624)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=4EAA25)
![](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=007396)
![](https://img.shields.io/badge/Code-TypeScript-informational?style=flat&logo=typescript&logoColor=white&color=3178C6)
![](https://img.shields.io/badge/Code-Android-informational?style=flat&logo=android&logoColor=white&color=3DDC84)
![](https://img.shields.io/badge/Code-Angular-informational?style=flat&logo=angular&logoColor=white&color=DD0031)
![](https://img.shields.io/badge/Database-Postgres-informational?style=flat&logo=postgresql&logoColor=white&color=4169E1)
![](https://img.shields.io/badge/Database-Microsoft_SQL_Server-informational?style=flat&logo=microsoft-sql-server&logoColor=white&color=CC2927)
![](https://img.shields.io/badge/Cloud-Amazon_AWS-informational?style=flat&logo=amazon-aws&logoColor=white&color=232F3E)
![](https://img.shields.io/badge/Cloud-IBM_Cloud-informational?style=flat&logo=ibm-cloud&logoColor=white&color=1261FE)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=007ACC)
![](https://img.shields.io/badge/Editor-IntelliJ_IDE-informational?style=flat&logo=intellij-idea&logoColor=white&color=000000)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=2496ED)
![](https://img.shields.io/badge/Tools-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=6aa6f8)
