# Helm Charts

## Publish

```bash
helm create chart
helm lint chart
helm package chart
mv chart-0.1.0.tgz docs
helm repo index docs
git add -i
git commit -av
git push origin master
```
