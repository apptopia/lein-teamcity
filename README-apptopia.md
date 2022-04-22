This is fork of https://github.com/nd/lein-teamcity

https://plugins.jetbrains.com/plugin/9090-leiningen

we're using it in our Teamcity just like it's described in README.md section Usage

more details:
- the generation of `~/.lein/profiles.d/teamcity.clj` is done as part of build step
- and the tests run is done just like described in that very section 
```
lein with-profile +teamcity do test
```

NOTE it's possible to run `lein test` without that and we will get the results - build log, commit publisher etc and it would be pretty fine
but it would be less convenient
