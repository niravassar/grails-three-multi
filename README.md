# grails-three-multi

This multi project build shows how `assemble` with gradle 4 and grails 3 rest-api (created from the rest-api profile) app works.

This works

- start in grails-three-multi/
- `cd grails-three-rest-api`
- `gradlew assemble`
- `java -jar build\libs\grails-three-rest-api-0.1.jar`

This works also from the top level

- start in grails-three-multi
- `gradlew grails-three-rest-api:assemble`
- `java -jar grails-three-rest-api\build\libs\grails-three-rest-api-0.1.jar`