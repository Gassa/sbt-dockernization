A day with sbt
==============

Code from a meetup presentation at [Göteborgs Scalaentusiaster](http://www.meetup.com/Scala-Geats/events/230320224/).

[Slides](http://www.slideshare.net/marcuslonnberg/a-day-with-sbt)

sbt docker:publishLocal
docker run -dit -p 8080:8080 a-day-with-sbt:1.0
curl -X POST -d "[1, 2, 3]" -H "Content-Type: application/json" http://localhost:8080/sort

Plugins used

- [sbt-buildinfo](https://github.com/sbt/sbt-buildinfo)
- [sbt-docker](https://github.com/marcuslonnberg/sbt-docker)
- [sbt-git](https://github.com/sbt/sbt-git)
- [sbt-native-packager](https://github.com/sbt/sbt-native-packager)
- [sbt-updates](https://github.com/rtimush/sbt-updates)
- [sbt-revolver](https://github.com/spray/sbt-revolver)
