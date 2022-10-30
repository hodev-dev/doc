nano dev.sh
```
!#/bin/bash
php artisan serve &
P1=$!
npm run dev &
P2=$!
wait $P1 $P2
```
```
sudo chmod 700 dev.sh
```