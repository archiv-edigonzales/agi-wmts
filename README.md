# agi-wmts

```
docker build -t sogis/plantuml .
cat agi-wmts.puml |  docker run --rm -i sogis/plantuml -tpng > agi-wmts.png
```