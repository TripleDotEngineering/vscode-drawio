Use `returnbounds` to get xml right after load:

```js
// Sends the bounds of the graph to the host after parsing
if (urlParams['returnbounds'] == '1' || urlParams['proto'] == 'json')
```

---

To publish the package

```bash
vsce package
vsce publish --packagePath ./tripledot-vscode-drawio-*.vsix
```
