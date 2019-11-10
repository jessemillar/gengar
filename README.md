[![Preview](dev/concept.png)](https://gam.fitbit.com/gallery/clock/2b28bb1d-5002-4fd1-a32b-59443be7596a)

## CLI Usage
```
npm install
npx fitbit
fitbit$ bi
```

## Color Replacement
> Desired color on left, color to replace on right
```
mogrify -format png -fill "#ccaccb" -opaque "#f2f2f0" large-*.png
mogrify -format png -fill "#ccaccb" -opaque "#f2f2f0" small-*.png
mogrify -format png -fill "#8e478c" -opaque "#bd515a" small-*.png
mogrify -format png -fill "#8e478c" -opaque "#bd515a" large-*.png
```

## Quick Image Resize
> Images stolen from my other watch face were double-sized to make pixels more visible
```
mogrify -format png -filter point -resize 50% large-*.png
mogrify -format png -filter point -resize 50% small-*.png
```