# It works?

## Instalacja nodejs
wget https://nodejs.org/dist/v8.11.1/node-v8.11.1-linux-x64.tar.xz
tar xf node-v8.11.1-linux-x64.tar.xz
mv node-v8.11.1-linux-x64 node
sudo cp -r node/{bin,include,lib,share} /usr/

## Sortowanie tablicy asocjacyjnej po polu

array_multisort(array_column($myArray, 'order_field_name'), SORT_ASC, $myArray);


## Instalowanie przez bower

./node_modules/.bin/bower install http://github.com/x/y.git --save 
