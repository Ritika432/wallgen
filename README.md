# WallGen
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)   [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)  
[![](https://img.shields.io/badge/Demo-yellow.svg?style=for-the-badge)](http://wallgen.herokuapp.com/)


Generates HQ poly wallpapers

## Installation 

`pip install --editable .`

## Usage

### `wallgen`

```
Usage: wallgen [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  pattern  Generate a HQ image of a beautiful pattern
  poly     Generates a HQ low poly image
```

### `wallgen poly --help`

```
Usage: wallgen poly [OPTIONS] SIDE

  Generates a HQ low poly image

Options:
  --colors TEXT...  use custom gradient, e.g --colors #ff0000 #0000ff
  --np INTEGER      number of points to use, default = 100
  --show            open the image
  --help            Show this message and exit.
```

### `wallgen pattern --help`


```
Usage: wallgen pattern [OPTIONS] SIDE

  Generate a HQ image of a beautiful pattern

Options:
  --sq              use squares instead of rhombus
  --colors TEXT...  use custom gradient, e.g --colors #ff0000 #0000ff
  --show            open the image
  --help            Show this message and exit.
```

## Examples

## `wallgen poly 2000 --colors #dd0000 #4455ff`

![](./images/demo1.png)

## `wallgen poly 2000 --colors #dc2221 ##35d7d6`

![](./images/demo2.png)

## `wallgen pattern 2000 --sq --colors #dd0000 #4455ff`

![](./images/demo3.png)


## Screenshots

## `Homepage`

![image1](https://user-images.githubusercontent.com/35899910/46815188-0a84d280-cd98-11e8-9d74-20ffd4239148.png)

## `Poly_Demo`

![image11](https://user-images.githubusercontent.com/35899910/46815367-664f5b80-cd98-11e8-9247-1e96dac8b8e1.png)

## `Wallgen1`

![image12](https://user-images.githubusercontent.com/35899910/46815734-22108b00-cd99-11e8-9ec5-006118b87532.png)

## `Square_Demo`

![image21](https://user-images.githubusercontent.com/35899910/46815830-53895680-cd99-11e8-8795-fa8f6731e153.png)

## `Wallgen2`

![image22](https://user-images.githubusercontent.com/35899910/46815900-76b40600-cd99-11e8-8123-966446e9c0b7.png)

