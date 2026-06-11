<!--HEAD-->

<img alt="3SPO" src="SAVE_3SPO.png" max-width=100%>

<!--HEAD-->
<!--SEPARATOR-->

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!--ABOUT ME-->

```java 
import org.springframework.boot.CommandLineRunner;
import org.springframework.context.annotation.Profile;
import org.springframework.stereotype.Component;

import com.github.freva.asciitable.AsciiTable;
import com.github.freva.asciitable.Column;

import java.util.*;

@Component
@Profile("developer")
public class THREESPO implements CommandLineRunner {
    private final String handle = "3spoo";
    private final String[] pronouns = {"he", "him"};
    private final String status = "Cybersecurity Student & Practitioner";
    private final String FACT = "Still learning... and breaking things.";

    // STILL_LEARNING
    private final Map<String, List<String>> stack = new StackBuilder()
        .add("languages", "Java", "C", "C++", "C#", "Python", "PHP", "JavaScript", "Bash")
        .add("web", "HTML5", "CSS3", "Spring", "Markdown")
        .add("databases", "MySQL")
        .add("tools", "Git", "GitHub", "Docker", "Figma", "Vim")
        .add("ides", "VS Code", "Visual Studio", "CLion", "GoLand", "PhpStorm", "PyCharm", "WebStorm", "Android Studio")
        .add("os", "Arch Linux", "Kali", "Debian", "Fedora", "Ubuntu", "Windows 11")
        .add("terminal", "Bash", "PowerShell", "Windows Terminal")
        .build();

    private final Map<String, Integer> skillLevel = new LinkedHashMap<>() {{
        put("Web Pentesting", 82);
        put("OSINT", 75);
        put("Forensics", 70);
        put("Crypto Analysis", 68);
        put("Blue / Red Team", 60);
        put("Reverse Eng.", 55);
        put("Binary Exploit", 48);
    }};

    private final Set<String> roles = Set.of(
        "CTF Player", "Puzzle Teamer", "ITP Organizer & Player"
    );

    private final Map<String, String> socials = new LinkedHashMap<>() {{
        put("GitHub", "github.com/3spoo");
        put("Instagram", "@espoo.fabio");
        put("TikTok", "@espoo.fabio");
    }};

    private final Set<String> interests = Set.of(
        "CTF challenges", "Security tooling", "InfoSec", "Linux"
    );

    private static class StackBuilder {
        private final Map<String, List<String>> map = new LinkedHashMap<>();

        public StackBuilder add(String category, String... items) {
            map.put(category, List.of(items));
            return this;
        }

        public Map<String, List<String>> build() {
            return Collections.unmodifiableMap(map);
        }
    }

    @Override
    public void run(String... args) {
        System.out.print(this);
    }

    // CONTACT ME ON MY SOCIALS...
}
```
<br>

<!--ABOUT ME-->
<!--STATS: shadow_red, nord-->

<div align="center" style="width: 100vw; overflow-x: auto;">
  <img
    src="https://streak-stats.demolab.com?user=3spoo&theme=nord&hide_border=true"
    alt="GitHub Stats"
    style="width: 900vw;"
  />
</div>

<br>

<!--STATS-->
<!--THE END-->


<!--SEPARATOR
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
<br>
-->


<!--FOOTER
<div align="center">
   <em align="center">Errare umanum est perseverare autem diabolicum...
   </em>
</div>
-->
