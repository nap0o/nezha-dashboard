## 更新geoip.db

### 首次执行
```
git tag v0.20.13
git push origin v0.20.13
```
### 非首次执行
```
git tag -d v0.20.13
git push origin --delete tag v0.20.13
git tag v0.20.13
git push origin v0.20.13
```

```
2025-04-12 21:40
```