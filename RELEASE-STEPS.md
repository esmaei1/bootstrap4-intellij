- Bump version in `.version` file
- Update version in `build.gradle` file
- `./gradlew regenerate` will regenerate `plugin.xml`, `bootstrap.xml`, `font-awesome.xml` & `README.md`
- Update `CHANGELOG.md` with release notes
- `git add .` will stage all changes for commit
- `git commit -m "<Changes>"` will commit to local git repo
- `git tag -a <version> -m "<Release notes>"` will create tag with the latest version
- `git push && git push origin <version>` will push both the code & the tags to github 
- `./gradlew clean publishPlugin` will publish to jetbrains plugin repo
