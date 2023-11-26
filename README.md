## Build
```
flatpak-builder --force-clean build-dir org.eclipse.ChemClipse.yaml
```

### Test
```
flatpak-builder --user --install --force-clean build-dir org.eclipse.ChemClipse.yaml
flatpak run org.eclipse.ChemClipse
```
