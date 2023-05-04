### <p align="center"> 👋 Hi there! I'm Filip and I'm glad you're here!</p> 
<p align="center">
<a href="https://www.linkedin.com/in/filip-cyboran-882a89225/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/filip-cyboran-882a89225/" height="30" width="40" /></a>
</p>
<p align="center"><img src="https://komarev.com/ghpvc/?username=cyboranf&label=Profile%20views&color=0e75b6&style=flat" alt="cyboranf" /> 
</p>

#### <p align="center">🚀 Technologies I'm currently mastering</p> 
   
![Java](https://img.shields.io/badge/Java-17-blue?logo=java)
![Spring](https://img.shields.io/badge/Spring-5.3-blue?logo=spring)
![C](https://img.shields.io/badge/C-gray?logo=c)
![assembly](https://img.shields.io/badge/assembly-language-blue?logo=assembly)
![PHP](https://img.shields.io/badge/PHP-8.2-blue?logo=php)
![Laravel](https://img.shields.io/badge/Laravel-10-blue?logo=laravel)
![JavaScript](https://img.shields.io/badge/JavaScript-ES11-blue?logo=javascript)
![HTML](https://img.shields.io/badge/HTML-5-blue?logo=html)
![CSS](https://img.shields.io/badge/CSS-gray?logo=css)
![MySQL](https://img.shields.io/badge/MySQL-8.0.22-blue?logo=mysql)
![Postman](https://img.shields.io/badge/Postman-gray?logo=postman)
![Github](https://img.shields.io/badge/Github-gray?logo=github)
![Docker](https://img.shields.io/badge/Docker-gray?logo=docker)
![linux](https://img.shields.io/badge/linux-gray?logo=linux)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2020.2.3-blue?logo=intellij-idea)
![CLion](https://img.shields.io/badge/CLion-2020.2.3-blue?logo=clion)
![PyCharm](https://img.shields.io/badge/PyCharm-2020.2.3-blue?logo=pycharm)
![PHPstorm](https://img.shields.io/badge/PHPStorm-2020.2.3-blue?logo=phpstorm)

<br>

<h2 align="center"><img src="https://media0.giphy.com/media/AynUwd5uKhIevEWx54/giphy.gif?cid=ecf05e47iywvucds9x9pdb72x2aflphojug33t8j2izgk2hb&rid=giphy.gif&ct=s" width="50">𝚂𝚃𝙰𝚃𝚂<img src="https://media0.giphy.com/media/AynUwd5uKhIevEWx54/giphy.gif?cid=ecf05e47iywvucds9x9pdb72x2aflphojug33t8j2izgk2hb&rid=giphy.gif&ct=s" width="50"></h2>
<div align="center">
<img src="https://streak-stats.demolab.com?user=cyboranf&mode=daily&theme=react&hide_border=true&border_radius=5&order=3" height="150" alt="streak graph"  />
</div>
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=cyboranf&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=react&locale=en&hide_border=true&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=cyboranf&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=react&hide_border=true&order=2" height="150" alt="languages graph"  />
</div>

<br>


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



