### 👋 Hi there! I'm Filip and I'm glad you're here! 
<p align="center">
<a href="https://www.linkedin.com/in/filip-cyboran-882a89225/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/filip-cyboran-882a89225/" height="30" width="40" /></a>
</p>

#### 🚀 Technologies I'm currently mastering

![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![Spring](https://img.shields.io/badge/Spring-5.3-blue?logo=spring)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2020.2.3-blue?logo=intellij-idea)
![MySQL](https://img.shields.io/badge/MySQL-8.0.22-blue?logo=mysql)
![JavaScript](https://img.shields.io/badge/JavaScript-ES11-blue?logo=javascript)


#### 👨‍💻 Readme was created with some help from the community! ❤️
- [badges/shields](https://github.com/badges/shields)
-------

#### 🖊 Let's start with short introduction!

```Java
package io.github.cyboranf.cyboranf.domain.entities;
import java.util.Map;
import java.util.stream.Collectors;
public class GitHubBio extends Bio {
    private final String profile;
    private final Map<String, String> bio;
    public GitHubBio() {
        this.bio = Map.of(
             - 🔭 I’m currently working on MeetexApp
             - 🌱 I’m improving my java skill
             - 💬 Ask me about my knowledge
             - 📫 How to reach me: cyboranf@gmail.com
        );
        this.profile = "https://github.com/cyboranf";
    }
    public GitHubBio(String profile, Map<String, String> bio) {
        this.profile = profile;
        this.bio = bio;
    }
    @Override
    public String getBio() {
        return bio.keySet()
                .stream()
                .map(key -> "- " + key + " **" + bio.get(key) + "**")
                .collect(Collectors.joining(System.lineSeparator()));
    }
    public String getProfile() {
        return profile;
    }
}



