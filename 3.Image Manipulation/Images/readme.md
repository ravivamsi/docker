# Images 

## Prune

```terminal
$ docker image prune

or

$ docker image prune -a

or

$ docker image prune -a -f
```

![PruneImage](./media/imageprune.svg)

## Remove

```terminal
$ docker image rm <image name>

or

$ docker image rm <image id>
```

![RemoveImage](./media/imagerm.svg)

## Tagging

```terminal
$ docker image tag <source image name:tag> <target image name:tag>
```
![TagImage](./media/tagimage.svg)

## Inspect

Inspect Details of Image

```
$ docker image inspect <image name> 

or 

$ docker image inspect <image id>
```

![InspectImage](./media/inspectimage.svg)

## List 

List all Images


```
$ docker images
```

```
$ docker images --all 

or 

$ docker images -a
```

```
$ docker images --quiet

or

$ docker images -q
```

![ListImages](./media/listimagescli.svg)

## Layers

### Display

### Modify Image to Single Layer


## History

```
$ docker image history <image name>

or 

$ docker image history <image id>
```

![ImageHistory](./media/imagehistory.svg)