Pseudocode for Sprint 1

1) Pull weather status from open-meteo.com
2) Load rain and temperature into memory

if
temperature:
hot < 18C
cold => 18

rain:
positive =< 40%
negative > 40%

if rain
    and hot = display umbrella & shorts
    and cold = display umbrella and jacket

if not rain
    and hot = display sunglassess and shorts
    and cold = display sunglassess and jacket

Print output stays open until next "API pull"
Print output has timestamp 