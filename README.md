```
sudo pacman -Sy figlet

cat EOF < .bashrc >>
export JAM=$(date +%k)
if [[ 10 < "$JAM" ]] && [[ "$JAM" < 20 ]]
then
        figlet K o n i c h i w a !
elif [[ 0 < "$JAM" ]] && [[ "$JAM" < 10 ]]
then
        figlet O h a i y o !
else
        figlet K o n b a w a !
fi
EOF
```
