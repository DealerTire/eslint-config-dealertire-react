# eslint-config-dealertire-react
eslint base config for React projects at Dealer Tire

# Install Peer Deps

```sh
(
  export PKG=eslint-config-dealertire-react;
  npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs npm install --save-dev "$PKG@latest"
)
```

# Usage

Configure eslint to extend this package:

```json
{
  "extends": "dealertire-react",
}
```
