dev env:  
build: werf build --platform linux/amd64 --dev  
run:  werf run  --platform linux/amd64 --docker-options="-d -p 80:3000" --dev  

build prod env: werf build  
run: werf run --docker-options="-d -p 80:3000"
