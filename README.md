# knowledge
List of stuff I have learnt ...

## CLI

### 🖥 Capture screenshots automatically in OSX

```sh
i=1; while true; do screencapture -C -m -t jpg -x ~/captures/$i.jpg; let i++; sleep 1; done
```
