build:
	yarn install
	mkdir -p dist/{css,js}
	cp node_modules/normalize.css/normalize.css dist/css/normalize.css
	./node_modules/.bin/sass src/scss/neominimal.scss dist/css/neominimal.css --no-source-map
	rm -rf ../static
	mv dist ../static

clean:
	rm -rf node_modules
	rm -rf dist