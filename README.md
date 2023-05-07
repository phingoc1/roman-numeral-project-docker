# Roman numerals docker files

```git clone git@github.com:phingoc1/roman-numeral-project-docker.git```

#### Laravel Backend
1.  [Download](https://github.com/phingoc1/roman-numeral-project-backend/) backend repo into ```uke-docker/backend-laravel/src```
2.  Rename ```.env.example``` to ```.env``` inside ```uke-docker/backend-laravel/src``` and set DB credentials according found inside ```docker-compose.yml```
3. Cd ```into uke-docker/backend-laravel``` and run ```docker-compose up```
3. Run ```docker-compose run --rm npm install``` and ```docker-compose run --rm npm run dev``` 
4. Run ```docker-compose run -rm artisan:migrate```
5. Open browser and navigate to ```http://localhost:8000```


#### Vue frontend
1.  [Download](https://github.com/phingoc1/roman-numeral-project-frontend/) frontend repo into ```uke-docker/frontend-vue/src```
2.  Cd ```into uke-docker/frontend-vue``` and run ```docker-compose up```
3. Open browser and navigate to ```http://localhost:8080```