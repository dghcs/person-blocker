# Person Blocker

A script to automatically "block" people in images (like the Black Mirror episode White Christmas) using [Mask R-CNN](https://github.com/matterport/Mask_RCNN).

## Maintainer

Max Woolf ([@minimaxir](http://minimaxir.com))

*Max's open-source projects are supported by his [Patreon](https://www.patreon.com/minimaxir). If you found this project helpful, any monetary contributions to the Patreon are appreciated and will be put to good creative use.*

## Examples

```shell
python3 person_blocker.py -i images/img1.jpg
```

```shell
python3 person_blocker.py -i images/img2.jpg -c '#c0392b' -o 'horse'
```

```shell
python3 person_blocker.py -i images/img3.jpg -c "(0, 0, 255)" -o 'bus' 'truck'
```

## License

MIT