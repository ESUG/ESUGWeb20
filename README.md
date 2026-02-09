This is a draft of a version of the ESUG web site based on Foliage. 
This is a work in progress. 
It should use the templated Microdown writer.



To run foliage once deployed. 

```
./build/foliage --source site --target generated
```

Potentially on the command line for the dev version we should do

```
Documents/Pharo/vms/130-x64/Pharo.app/Contents/MacOS/Pharo Documents/Pharo/images/P13-xxx/P13-xxx clap foliage  --source site --target generated
```

The following expression is handy to run a pillar (not foliage) on the command line and execute a development image 
as opposed to a deployed Pillar. 

```
Users/ducasse/Documents/Pharo/vms/130-x64/Pharo.app/Contents/MacOS/Pharo /Users/ducasse/Documents/Pharo/images/P13-PillarTemplatingLogic/P13-PillarTemplatingLogic.image clap build html index.md
```

