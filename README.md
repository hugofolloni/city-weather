# city-weather

## 🌧 About the project 
A website that shows the weather from your current location, accessing your geolocation by the browser. But, if you want, you can also request data from other places on earth, displaying the localtime too. Also, the background changes if is day or night on the place. For this project, I used 3 APIs, besides cors-anywhere. 
OBS: This is a project just like one of my firsts ever (with Vanilla JS), but now it was made with React, a technology that I'm studying.
__________________________________________________________________________________________________

Um site que mostra o tempo da sua atual localização, acessando sua localização pelo navegador. Porém, você também pode acessar dados climáticos de outros lugares ao redor do mundo, mostrando também a hora de acordo com o fuso horário. Além disso, o plano de fundo do site muda dependendo se é dia ou noite no local requisitado. Para este projeto, usei 3 APIs (minha primeira experiência usando-as), além de uma versão do cors-anywhere.
OBS: Esse projeto é uma releitura de um dos meus primeiros, mas agora foi feito com React, que é uma tecnologia que estou estudando.

## 🧔 User Story

The user can enter the website and see the weather for his current position. Also, he can search for look for another places. The plus on this project is the theme changer, with the background following the day/night changes on the searched place.

## 🎨 UI
☀️ Exemplo de Horário Diurno:
![image](https://user-images.githubusercontent.com/82226141/135192722-75230479-6629-48a4-aebd-c9df9f4ddbb5.png)

🌙 Exemplo de Horário Noturno:
![image](https://user-images.githubusercontent.com/82226141/135192701-001b77d6-e0c5-4a48-b802-8ec5635360e4.png)


## 🕹️ Technologies

- React
- JSON-server 

### APIs:

· cors-anywhere: used to get data from an external API and show it on the site.

· bigdatacloud: i get the location of the user (country, neighborhood, city...) based on the geolocation of the browser.

· darksky: i get the temperature and the icon of the place (by the browser or search).

· weatherapi: i get the information if it's day or night on the place and the location of the user when searched.

### Live:

You can check this project running [here](https://city-weather-live.netlify.app).

I have the old Vanilla JS version of the project too, that stills working,  and it's available to visit [here](https://cityweather-info.herokuapp.com/index.html).
