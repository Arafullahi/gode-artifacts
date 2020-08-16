# Gode-Artifacts

A artifact repository for gode related artifacts.


## Code repositories
- https://github.com/ibs-gode/gode-core

## How to install

Add the following to maven profile

>        <repository>
>          <id>github</id>
>          <name>GitHub ibs-gode Apache Maven Packages</name>
>          <url>https://maven.pkg.github.com/ibs-gode/gode-artifacts</url>
>        </repository>
        
## How to publish

Add the following in settings.xml

>     <server>
>       <id>github</id>
>       <username>USERNAME</username>
>       <password>TOKEN</password>
>      </server>

Remember to provide github username instead of USERNAME and generate personal token from github and provide it instead of TOKEN.

You can choose to provide distributionManagement as well.

## Reference
- https://docs.github.com/en/packages
