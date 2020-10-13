# hello-world
armazenamento de ideias
# com intuito elf=bot
auto 1800000 listas 'Combo EXP c/ 20x' | settargeting off | setcavebot off | stopattack | wait 2000 | useoncreature 9641 self | wait 2000 | useoncreature 3215 self | wait 1000 | useoncreature 9642 self | useoncreature 3726 self | wait 1000 | useoncreature 11454 self  | wait 1000 | useoncreature 9650 self | wait 1000 | useoncreature 10293 self | wait 1000 | useoncreature 10306 self | wait 1000 | | useitem 10316 | wait 1000 | useitem 11455 | wait 500 | wait 2000 | useoncreature 9641 self | wait 2000 | useoncreature 3215 self | wait 1000 | useoncreature 9642 self | useoncreature 3726 self | wait 1000 | useoncreature 11454 self  | wait 1000 | useoncreature 9650 self | wait 1000 | useoncreature 10293 self | wait 1000 | useoncreature 10306 self | wait 1000 | | useitem 10316 | wait 1000 | useitem 11455 | wait 500 | settargeting on | setcavebot on | wait 2000

auto 1 dontlist | if [$hppc < 90 && $hppc > 90] say 'exura vita' | if [$hppc < 95] say 'exura vita'

auto 100 dontlist | if [$key.6] crosshair 3180

collectitems 'empty' 3492 2812 2981 2984 3423 3031 3389 8103 3035 3725 3043 3447 8097 5801 6526 8090 7532 7993 8097 864 651 9018 8060 8022 11687 8864 9019 8154 8863 3368 3549 8062 7532 9604 8053 8862 2854' 3031 3492 3035 3043 3725 6529 238 3437 3549 8076 3040 2473 2469 2472 2471 2983 3507 3567 3391 3557 3079 3425 3047 2866 3161 3155 3164 3308 3079 2985 8532 |

foreach [allplayers] $daviscriptp if [$daviscriptp.name != $self.name && $daviscriptp.isfriend == 0] {setrelation [$daviscriptp.name] [enemy]} say Enemys: [$enemycount] Rebequinha Dashow ;D +: [$friendcount]
