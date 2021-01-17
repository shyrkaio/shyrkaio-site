# site
This is repository for the shyrka web site


## Build

```bash
mvn site site:run
```

## Deploy sur github page

Update  `settings.xml`:

```xml
<settings>
  <servers>

  <server>
      <id>github</id>
      <username>xxx</username>
      <password>xxx</password>
  </server>
  </servers>
</settings>
```

Active profil `deploy` by running :

```bash
mvn site -Pdeploy
```
