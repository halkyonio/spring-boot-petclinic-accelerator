# Accelerator Log

## Options
```json
{
  "branch" : "main",
  "description" : "",
  "icon" : "https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png",
  "name" : "spring-petclinic",
  "projectName" : "spring-boot-petclinic-accelerator",
  "url" : "https://github.com/halkyonio/spring-boot-petclinic-accelerator"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","name":"spring-petclinic","description":"","artifactId":"spring-boot-petclinic-accelerator","projectName":"spring-boot-petclinic-accelerator","branch":"main","url":"https://github.com/halkyonio/spring-boot-petclinic-accelerator"}
┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input10754059274270044464, --data-values-file, /tmp/accelerator-options560197646286573169.json, --output-files, /tmp/ytt-output5790603922762447968]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┗ ┗ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
