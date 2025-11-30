# Spooky Charm

## PrismLauncher Continuous Updating

On the instance custom commands put the following command on the _Pre-launch command_:

`"$INST_JAVA" -jar packwiz-installer-bootstrap.jar -s client https://github.com/blossom-garden/spooky-charm/raw/main/pack.toml`

If yo want to always download a specific version:

```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar -s client https://github.com/blossom-garden/spooky-charm/raw/{PUT VERSION NUMBER HERE}/pack.toml

# for 1.0.0

"$INST_JAVA" -jar packwiz-installer-bootstrap.jar -s client https://github.com/blossom-garden/spooky-charm/raw/1.0.0/pack.toml
```
