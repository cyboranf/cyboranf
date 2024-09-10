
```Java
package io.github.cyboranf.cyboranf.domain.entities;

import java.util.Map;
import java.util.stream.Collectors;

public class GitHubBio extends Bio {  
    private final String profile;
    private final Map<String, String> bio;

    public GitHubBio() {
        this.bio = Map.of(
            "Current Work", "I’m currently working at JitTeam",
            "Contact", "How to reach me: cyboranf@gmail.com"
        );
        this.profile = "https://github.com/cyboranf";

        // TODO: Implement the application I'm working on and establish a startup
    }

    public GitHubBio(String profile, Map<String, String> bio) {
        this.profile = profile;
        this.bio = bio;
    }

    @Override 
    public String getBio() {
        return bio.entrySet()
                .stream()
                .map(entry -> "- " + entry.getKey() + ": **" + entry.getValue() + "**")
                .collect(Collectors.joining(System.lineSeparator()));
    }

    // Getter for GitHub profile URL
    public String getProfile() {
        return profile;
    }
}                                                                                                                                         
```
