# knowledge
List of stuff I have learnt ...

## CLI

### 🖥 Capture screenshots automatically in OSX

```sh
i=1;while [ 1 ];do screencapture -t -C -m jpg -x ~/screenshots/$i.jpg; let i++;sleep 1; done
```
