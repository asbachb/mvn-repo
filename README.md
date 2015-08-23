This respository contains some maven artifacts which are not present in maven central. In order to use these artifacts you need to add following declaration to your pom.xml

    <repositories>
        <repository>
            <id>github-asbachb-releases</id>
            <url>https://raw.github.com/asbachb/mvn-repo/master/releases</url>
        </repository>
    </repositories>
