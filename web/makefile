build:
	docker build -t poupanca-web:1.0.0 .

run:
	docker run --name pw -d -p 8080:80 poupanca-web:1.0.0

dev:
	docker run --name pw -d -p 8080:80 -v .:/usr/share/nginx/html:ro poupanca-web:1.0.0